---
sidebar_position: 1
slug: /
title: Tandem
---

___

# Warning

### After getting the first feedback from Redwood community members on May 18, 2022, it become apparent that the Tandem project is all about Testing and Debugging. To correct that perception we are stating the right one: we are building a Redwood Cookbook where debugger is not the only tool in the developers tool box.

This application is being be recreated in the format similar to [how To](https://redwoodjs.com/docs/how-to/index) section of the Redwood Tutorial.

___
___
___

### _Testing and debugging_ of Redwood applications

1. [Tandem](https://rw-community.org/) tutorial application presents various articles on testing and debugging. Well known [Redwood Blog](https://github.com/adriatic/RedwoodBlog) application is used as the model for all testing and debugging techniques explained in this course.

2. Both [RedwoodJS tutorial](https://redwoodjs.com/docs/tutorial/foreword) and the [Tandem tutorial](https://rw-community.org/) are RedwoodJS applications. The **first** shows you how to build your first RWJS app (Redwood Blog) - and the **second** one presents testing and debugging methods using  the Redwood Blog app as the application to test and debug.

A typical debugging session is shown on the image below

<p align="center">
<img width="600" alt="image" src="https://user-images.githubusercontent.com/2712405/167678372-99cd74f1-c41d-4538-8716-c23e7c52ca26.png"/>
<br/>
<b>Image 1 - debugger and debugee</b>
</p>
<br/>

---

### A couple of innovations

Expanding on RedwoodJS existing documentation, this web site offers Redwood developers detailed information on `testing` and `debugging`. The  [how to](https://rw-community.org/) introduces several standard tools, placed in two sections. These sections [how to test](https://rw-community.org/how-to/testing/introduction) and [how to debug](https://rw-community.org/how-to/debugging/introduction) expand the RedwoodJS' existing [main online document set](https://redwoodjs.com/docs/introduction).

Very few startup companies can afford to create as good documentation as it is expected for a prominent startup like RedwoodJS. It became apparent that _providing a formal infrastructure_ to its developers community, will help reducing the load on Redwood core team, as well as allowing more application specific view of these documents.

#### 1. Using the Redwood Blog application as the teaching model

Organization and design of the [Testing and Debugging](https://rw-community.org/) online website is a novel concept. We are using the source code of the [RedwoodJS tutorial](https://redwoodjs.com/docs/tutorial/foreword) as the context to explain the various testing and debugging tools. In other words the same application that is being built from scratch following the instructions from the Redwood tutorial, is being used (in its source form) as context for running tests and debugging methods and tools in this tutorial.

#### 2. Customers contributing to documentation efforts

Unlike the "main" documentation written mostly by RedwoodJS founders and core team members, this project expects the participation of RedwoodJS users (see [this article](https://community.redwoodjs.com/t/proposal-testing-and-debugging-project/2923`)) for details. The Docusarus based [website](https://rw-community.org) serves as the documentation framework, making the writers job nearly identical workflow using the core team developers. So, each specific document in this site is added or modified as a PR.

---

### Use case scenario and workflow

<br/>

<p align="center">
  <img width="360" src="https://user-images.githubusercontent.com/2712405/164993375-a0297688-af77-4734-9dc5-6581d2582eac.png" />
<br />
Testing and debugging with WebStorm IDE
</p>

1. Point the browser to <https://rw-community.org/>
2. Choose between `how to test` and `how to debug` in the `how to section`:

<p align="center">
  <img width="360" alt="image" src="https://user-images.githubusercontent.com/2712405/165111088-5f705f26-1d2a-4de2-a181-9d8a57210cda.png"/>
</p>

3. Consider the case where item 1 (`how to test`) followed by a click on `jest` was selected:

<p align="center">
<img width="360" alt="image" src="https://user-images.githubusercontent.com/2712405/165114504-1bce9947-3621-467f-bb5e-e226081f3302.png"/>clear
</p>

At this point (`jest` selected) the guided tutorial explaining testing with `jest` begins with the selection of the example to test. This selection is provided by this (tandem) application which knows where to extract the relevant set of source code samples from.
