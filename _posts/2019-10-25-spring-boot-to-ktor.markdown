---
layout: post
title: "Going from Spring to Ktor - part 0"
date: 2019-10-25 13:00:00
categories: [programming]
tags: [kotlin, spring boot, ktor, backend]
published: true
---

## Introduction
Spring Boot is the standard framework for backend services. Every backend service I write is in Kotlin with Spring Boot. I prefer Kotlin over Java because Kotlin is less verbose and much more concise. From the Kotlin community, more frameworks are being built. Ktor is one of them. What is Ktor?

> Ktor is a framework for building asynchronous servers and clients in connected systems using the powerful [Kotlin programming language](https://kotlinlang.org). 
>
> &mdash; <cite>[Ktor.io](https://ktor.io/)</cite>


## Research Questions
In this series we are going to explore Ktor and compare it to a simple Spring Boot service. In this adventure, there are many questions to be answered:

 - What is the performance of a Ktor application versus a Spring Boot application? 
 - What are the resource characteristics of both? 
   - What is the throughput?
   - What is the CPU usage?
   - What is the memory usage?
 - What is the complexity when services grow?
 - What are the coding conventions compared to each other?
 - What is the stability of the Ktor framework compared to Spring Boot?

## Follow the series
Come along this adventure of exploring Ktor and seeing how it works and performs. I will post tweets regarding this on my twitter handle [@martinbeentjes](https://twitter.com/martinbeentjes). I also will be sharing projects on GitHub when finished.
