---
sidebar-position: 2
title: devtools setup
---

### 1. Prepare the application used as debugging target

In order to illustrate the use of Chrome DevTools in a debugging task, we have to have an application to be debugged. Rather than creating such application with sufficient complexity needed to illustrate debugging practices, chosing the well known application that was built in the course of the [Redwood Tutorial](https://redwoodjs.com/docs/tutorial/foreword). This prebuilt application exists
 [here](https://github.com/adriatic/redwoodblog) so let's make a local clone, using the instruction defined in [using the example repo](https://redwoodjs.com/docs/tutorial/intermission#using-the-example-repo-recommended)

```
git clone https://github.com/adriatic/redwoodblog
cd redwoodblog
yarn rw prisma migrate dev
yarn rw prisma db seed
yarn rw g secret
yarn rw dev
```
resulting with:

<p align="center">
<img width="600" alt="image" src="https://user-images.githubusercontent.com/2712405/166114124-54b0daa6-130d-49d2-997a-f0cb814e158b.png"/>
<br/>
<b>Image 1 - Redwood Blog app running locally</b>
</p>
<br/>

---

## Start debugging the app

The plan is to step through the code of the [Authentication chapter](https://redwoodjs.com/docs/tutorial/chapter4/authentication). In order to be ready to do that, run the following two steps:

- Start the application from the terminal window
- Open the browser's Developer Tools window

<p align="center">
<img width="700" alt="image" src="https://user-images.githubusercontent.com/2712405/166124153-eb3ca0ac-1054-45cf-b9e1-5143323fcfc5.png"/>
<br/>
<b>Image 2 - Selecting the DevTools </b>
</p>
<br/>

This image shows the Redwood Blog application in the background and the user interface of the Chrome DevTools rendered on top. The yellow markers 1, 2 and 3 define the sequence of clicks needed to render DevTools.

Then, traverse the "application tree" to reach the `HomePage.js` (yellow marker 3 on Image 3) and set the breakpoint at line 5 (yellow marker 4 on Image 3). At that point restart the browser and observe that the "built in Chrome debugger" reached the brakpoint (yellow marker 5 on Image 3)
<br/>


<p align="center">
<img width="700" alt="image" src="https://user-images.githubusercontent.com/2712405/166124289-5642d716-944f-4f4f-b463-ef83d4be710a.png"/>
<br/>
<b>Image 3 - Setting a breakpoint</b>
</p>
<br/>

