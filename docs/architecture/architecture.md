---
layout: default
title: Architecture
nav_order: 4
description: "Architecture details."
permalink: /architecture
has_children: true
---

# Architecture
{: .fs-9 }

This document provides details on the technical aspects of the product, including a high-level presentation of the conceptual architecture and information about the software and hardware components.
{: .fs-6 .fw-300 }

---

The following paragraph briefly describes the execution flow of the service and gives a high-level overview of the overall components. 

The main flow of the mobile application starts when the user login into the application, providing a list of preferences to feed a machine learning algorithm. Once logged in, the user can search for movies and tv shows with various filters, create lists and collections of titles, interact with other users, receive notifications about subscribed topics, and eventually watch its statistics and gamification badges.
The user could also interact with a chatbot, "Munity", that provides different services such as giving general support, helping to choose a film and finally handling the integration with local theatres to reserve a seat.

Now we have a general overview and so we can go into the details of the components that make up the leading architecture.

<p align="center">
<img src="{{site.baseurl}}/assets/images/Architecture.png"/>
</p>

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## <a id="app"></a>Mobile application
In the last year, one of the most popular questions in our all mind has been "wouldn't be great to have a quick access to resources and applications through our smartphones?". Nowadays smartphones become more than just a communication device, because they are a kind of mirror or bridge for our work, life, entertainment and business. 

### React Native

It is an open-source application available on our git repository and provided as apk. We are talking about a hybrid app developed on **React Native**, a cross-platform mobile development framework that allows programmers to create apps for both iOS and Android in one simple language, TypeScript. Indeed React Native runs on React, an open-source library for building UI with JavaScript, this framework through a set of components builds a mobile application with a native look and feel. Due to the pretty simple learning curve and well-balanced performance React Native it’s the perfect compromise for our application.

## <a id="mcs"></a>Backend

Microservices are a style of service-oriented architecture (SOA) where the app is structured on an assembly of interconnected services. With microservices, the application architecture is built with lightweight protocols. The services are finely seeded in the architecture. Microservices disintegrate the app into smaller services and enable improved modularity. 

Compared to its predecessor, the monolithic architecture, microservices are hands down more beneficial. 

{: .note }
> This section is still not completed.


### Node.js
As an asynchronous event-driven JavaScript runtime, Node.js is designed to build scalable network applications. 

{: .note }
> This section is still not completed.

### Nest
Nest is a framework for building efficient, scalable Node.js server-side applications. It uses modern JavaScript, is built with TypeScript (preserves compatibility with pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

Under the hood, Nest makes use of Express, but also, provides compatibility with a wide range of other libraries, like e.g. Fastify, allowing for easy use of the myriad third-party plugins which are available.

{: .note }
> This section is still not completed.
