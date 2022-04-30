---
sidebar-position: 2
title: example 1
---


# Example 1

### tracing the authentication code

Follow the instructions in the [example-1](https://rw-community.org/how-to/debugging/chrome/chrome). Also have the [authentication](https://redwoodjs.com/docs/tutorial/chapter4/authentication) chapter in the [Redwood Tutorial](https://redwoodjs.com/docs/tutorial/foreword) ready, so you can trace through the code, using the explanations from both [Tandem](https://rw-community.org/how-to/debugging/introduction) and [Redwood](https://redwoodjs.com/docs/tutorial/foreword) tutorials.

---
---

## Building the app

Let's start with a simple practice - step through the authentication code of the Redwood Tutorial Blog application which you can fetch [here](https://github.com/adriatic/tandem-tutorial-samples) - main branch. This application is a clone of the original [redwood-tutorial-blog](https://github.com/redwoodjs/redwood-tutorial), and the "main branch" attribute indicates that this application is not "spiked" with any induced problems.

1. In order to start, create a local clone of the [finished Redwood Blog](https://github.com/adriatic/tandem-tutorial-samples) in the folder `/Users/nik/tandem` (replace `nik` with your user name)

2. Make this application ready for execution (as explained in the [Setup](https://github.com/redwoodjs/redwood-tutorial#setup) note of the [Readwood Blog app](https://github.com/redwoodjs/redwood-tutorial#redwood-tutorial-app)), by running the steps below:

```
cd sample-1
yarn install
yarn rw prisma migrate dev
yarn rw dev
```
If you are curious what all happens in the process of building this application (running the four commands shown above) check the [log](https://github.com/adriatic/tandem/issues/5) - otherwise, the application will be rendered in a new browser instance as shown below:  

<img width="948" alt="image" src="https://user-images.githubusercontent.com/2712405/166114124-54b0daa6-130d-49d2-997a-f0cb814e158b.png"/>
<br/>
<br/>


## Running the app in the Chrome browser

Step through the code of the [Authentication chapter](https://redwoodjs.com/docs/tutorial/chapter4/authentication).


