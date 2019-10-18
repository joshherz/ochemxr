# 1. OchemXR
>A VR/AR (also known collectively as XR) website utilizing the WebXR Device API as well as Facebook's separate, independent framework, React360. This project provides an engaging way to learn organic chemistry. Very handy for chemistry students with a shamefully short attention span (like me.)

![](ochemxrargif.gif)

SKIP TO [1.4.1. How to Run This Code](#141-how-to-run-this-code) if you're the TL;DR type.

## 1.2. Table of Contents
<!-- TOC -->
- [1. OchemXR](#1-OchemXR)
  - [1.2. Table of Contents](#12-table-of-contents)
  - [1.3. Overview](#Overview)
  - [1.4. Usage](#13-usage)
    - [1.4.1. API endpoints](#131-api-endpoints)
    - [1.4.2. Component](#132-component)
  - [1.4. Development Setup](#14-development-setup)
  - [1.5. Development Setup](#14-development-setup)
3. [Development](#development)
<!-- /TOC -->


## 1.3. Overview
**What is React360?**

React360 is Facebook's framework for supporting VR experiences on the web. React360 development is Javascript syntax heavy.



**What is WebXR?**

As a successor to the popular WebVR API, WebXR is an API currently in developement and a product of the Immersive Web Community Group which has contributors from Google, Microsoft, Mozilla, and others.  

It supports both VR and AR experiences on the web. Development is HTML syntax heavy and does not require as much in-depth knowledge in Javascript as React360. May be friendlier to those new to web development.



**Which one should a web developer interested in VR and AR use?**

While OchemXR.com uses a bit of both, most developers choose to use WebXR for ability to support complex applications, 6DOF, and AR. Others choose to use React360 as it has been around longer and is familar for React developers. 

But both are a means to an end to support XR experiences on the web. 



**An oChemXR AR experience**
 
> ![](oChemXrMoleculeModelGif.gif)

**An oChemXR VR experience**

_Placeholder for oChemXR VR experience VR gif_


**But...why? VR's dead.**

I LOVE Virtual Reality and Augmented Reality. I just wish more people saw the benefit beyond games (though don't get me wrong- I do love me some BeatSaber gaming seshes.) The applications are exciting and endless...
- AR-assisted surgeries
- molecular and protein visualization for designing new medications
- walking clients throuch 3D architectural designs before their building's even built
- etc, etc, etc... 

I also want to be a WebDev when I graduate. Unfortunately, I didn't realize this until senior year of my Chem degree at UCSB. With it being too late to switch to the CompSci major, I'm teaching myself how to program virtual reality experiences and fullstack websites. 



**Cool story bro. But I didn't need to read your whole autobiography. What does this program do?** 

Well... it explores the benefits and drawbacks of utilizing Facebook's framework, React360. It also demonstrates how XR platforms on the web may serve as a great alternative (but not replacement) for convential webpages.



**Why web? Why not just use Unity or UnrealEngine?**

Time-to-download/install can be a barrier-to-entry for downloadable apps. Meanwhile, websites are immediately accessible to the user. Plus, updates can be pushed instantly. 

Websites can also be designed to be cross-platform. For example, OChemXr.com can be opened in any browswer, from the Oculus VR browser on your shiny, new Oculus Quest... to Mobile Chrome on your smartphone. 


## 1.4. Usage

To run this code locally, follow the steps below.

### 1.4.1. How to Run This Code
1. Make sure you have Node installed for the npm commands you will run in step 4. (For installation, see https://nodejs.org/en/)
2. Make sure MongoDB is running locally (For installation and running MongoDB, see https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/#run-mongodb)
3. Clone this repo
4. Open terminal in the cloned folder,
   - To install dependencies, run ```  npm install  ```
   - To run MongoDB, ``` mongod --config /usr/local/etc/mongod.conf ``` (run in a 2nd terminal tab/window)
   - To run this app for development, run ```  npm run dev  ```
5. Open [localhost:8081](http://localhost:8081/) in the browser

### 1.4.2. API endpoints
- `GET ______` 
  - returns data from entry with specified id
- `POST ________` 
  - pushes a new entry to the database
- `PUT _______`
  - edits entry 
- `DELETE ______` 
  - removes entry with specified id from database


### 1.4.3. Dependency Requirements
- Node 6.13.0
These dependencies will be added to your auto-created node_modules folder when you run "npm install" command in your cloned folder in the terminal 
- React
- React-DOM
- React360 framework
- MongoDB
- express
- body-parser
- cors
- mongodb
- mongoose
- webpack
- docker
- http-server
- etc



