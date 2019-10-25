---
layout: post
title: "Going from Spring to Ktor - part 0"
date: 2019-10-21 13:00:00
categories: [programming]
tags: [kotlin, spring boot, ktor, backend]
published: true
---

## Introduction

Spring Boot is the standard framework for backend services. Ktor is a web framework  written  in Kotlin. In this series we will explore trying out Ktor instead of  Spring.

## Why Ktor?

I am write in Kotlin when it comes to backend services.  I prefer it over Java because it is less verbose and much more concise.

## Goals of this series

### Developer experience

As a developer writing Spring applications is really straight forward  and easy. How is that experience with Ktor? Is it as intuitive as  Spring Boot?

### Performance

What is the performance of a Ktor application versus a Spring Boot application? What are the resource characteristics of both?

For this we are going to deploy it into a fat jar in a Docker image (with the same specs) and see how both are performing.

### Gaining knowledge

Besides that we will also gain knowledge  about doing such experiments. And sharing is caring, thus we share  the knowledge we have gathered in the process.
