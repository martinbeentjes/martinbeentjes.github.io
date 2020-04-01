---
layout: post
title: "Setting up a fullstack web application using Spring Boot and ReactJS"
date: 2019-10-25 13:00:00
categories: [programming]
tags: [kotlin, spring boot, react, backend, frontend, fullstack]
published: false
---

This setup will give you a monolithic feeling. Yes, I did that on purpose. I do not hate monoliths. I hate the spaghetti in monolithic projects. 

We will be using the React framework for the frontend, maybe sometime we will be implementing TypeScript as well. Spring Boot is used for the backend using Kotlin as the language used.

React consists of many source files containing the app, components and configuration (and many more things). To be able to use this in our frontend, we will be building the JavaScript into a bundle file which will be included in the `index.html` of the Thymeleaf template.

The only thing that is still interesting to setup a run configuration in your IDE to implement automatic bundle generation so we do not have to manually restart Spring Boot, but that is something to build or use.
