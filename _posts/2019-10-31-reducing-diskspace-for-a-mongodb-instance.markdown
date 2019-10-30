---
layout: post
title: Reducing diskspace for a MongoDB instance
date: 2019-10-31
tags: [devops, mongodb, database]
published: false
---

## compact

MongoDB is a datastore which is often used when storing big blobs of data. It has the characteristic to not release diskspace when a lot of data is removed. When you have 5GB of data stored and try to remove 2GB of that, MongoDB will not release that 2GB of diskspace. The disk space will stay at 5GB. To actually reduce the disk space of a MongoDB database the `compact` command can be executed. Running the `compact` command places a block on all other operations at the database level. The `compact` command works at a collection level. To release diskspace previously used for `myMassiveData` collection, the following command can be executed:

```js
db.runCommand({compact:'myMassiveData'})
```

## MMAPv1

Using the `compact` command only works if you are not using the MMAPv1 engine. To release diskspace for a MongoDB instance using MMAPv1, the command `repairDatabase` can be executed on a database level. **Warning**: `repairDatabase` requires double the database size with an extra 2GB.

```js
db.repairDatabase()
```
