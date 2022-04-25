---
sidebar_position: 1
slug: /
---

# Introduction

Expanding on RedwoodJS existing documentation, this web site offers Redwood developers detailed exercises on `testing` and `debugging`. The  [how to](https://rw-community.org/cookbook/introduction) using several standard tools, placed in two sections. These sections [how to test](https://rw-community.org/how-to/testing/introduction) and [how to debug](https://rw-community.org/how-to/debugging/introduction) expand the RedwoodJS' existing [main online document set](https://redwoodjs.com/docs/introduction).

Very few startup companies can afford to create as good documentation as it is expected for an excellent startup like RedwoodJS. We realized that _providing a formal infrastructure_ to its developers community, will help reducing the load on Redwood core team, as well as allowing more application specific view of these documents.

Organization and design of the [Testing and Debugging](https://rw-community.org/) online website is a novel concept. We are using the source code of the [RedwoodJS tutorial](https://redwoodjs.com/docs/tutorial/foreword) as the context to explain the various testing and debugging tools. In other words the same application that is being built from scratch following the instructions from the Redwood tutorial, is being used (in its source form) as context for running tests and debugging methods and tools in this tutorial.

There is another novel approach - unlike the "main" documentation written mostly by RedwoodJS founders and core team members, it is a project that expects the participation of RedwoodJS contributors: (see [this article](https://community.redwoodjs.com/t/proposal-testing-and-debugging-project/2923`)) for details. The Docusarus based [website](https://rw-community.org) serves as the documentation framework, making the writers job nearly identical workflow using the core team developers. So, each specific document in this site is added or modified as a PR.

---
### Use case scenario and workflow

<br/>

<p align="center">
  <img width="360" src="https://user-images.githubusercontent.com/2712405/164993375-a0297688-af77-4734-9dc5-6581d2582eac.png" />
<br />
<b>Testing and debugging flow diagram</b>
</p>

Typical use case scenario:

1. Point the browser to https://rw-community.org/
2. Choose between `how to test` and `how to debug` in the `how to section`:

<p align="center">
  <img width="360" alt="image" src="https://user-images.githubusercontent.com/2712405/165111088-5f705f26-1d2a-4de2-a181-9d8a57210cda.png"/>
<br/>
</p>

3. Consider the case where item 1 (`how to test`) followed by a click on `jest` was selected:

<p align="center">
<img width="360" alt="image" src="https://user-images.githubusercontent.com/2712405/165114504-1bce9947-3621-467f-bb5e-e226081f3302.png"/>
<br/>
</p>

At this point (`jest` selected) the guided tutorial explaining testing with `jest` begins with the selection of the example to test. This selection is provided by this (tandem) application which knows to extract the relevant set of source code samples from 


