---
sidebar-position: 2
title: devtools setup
---


### 1. Fetch and Build the Redwood Blog app

In order to illustrate the use of Chrome DevTools in a debugging task, we have to have an application to be debugged. 
Let's start with a simple practice - step through the authentication code of the Redwood Tutorial Blog application which you can fetch [here](https://github.com/adriatic/tandem-tutorial-samples) - main branch. This application is a clone of the original [redwood-tutorial-blog](https://github.com/redwoodjs/redwood-tutorial), and the "main branch" attribute indicates that this application is not "spiked" with any induced problems.

1. Start, by creating a local clone of the [semi-finished Redwood Blog](https://github.com/adriatic/tandem-tutorial-samples) in the folder `/Users/nik/tandem` (replace `nik` with your user name)

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


## Running the app 
#### in the Chrome browser

The plan is to step through the code of the [Authentication chapter](https://redwoodjs.com/docs/tutorial/chapter4/authentication). In order to get there, let's get to the basic setup:

- Start the application from the terminal window
- Open the browser's Developer Tools window
<img width="918" alt="image" src="https://user-images.githubusercontent.com/2712405/166124153-eb3ca0ac-1054-45cf-b9e1-5143323fcfc5.png"/>

Then, traverse the "application tree" to reach the `HomePage.js` (yellow marker 3) and set the breakpoint at line 5 (yellow marker 4). At that point restart the browser and observe that the "built in Chrome debugger" reached the brakpoint (yellow marker 5)

<img width="1231" alt="image" src="https://user-images.githubusercontent.com/2712405/166124289-5642d716-944f-4f4f-b463-ef83d4be710a.png"/>

