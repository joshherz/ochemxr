# 1. OchemXR
>A VR/AR (also known collectively as XR) website for learning organic chemistry using the WebXR Device API and Facebook's framework React360. This project serves to provide an engaging way to learn organic chemistry for those who have a shamefully short-attention span (AKA me.) 

SKIP TO [1.3.1. How to run this code](#131-how-to-run-this-code) if you're a TL;DR type of guy like me.

*What is React360?* 

React360 is Facebook's framework for supporting VR experiences on the web. React360 development is Javascript syntax heavy.

*What is WebXR?*

The WebXR Device API is a product of the Immersive Web Community Group which has contributors from Google, Microsoft, Mozilla, and others. A successor to the popular WebVR API, WebXR is an API currently in developement. It supports both VR and AR experiences on the web using ThreeJS. Development is HTML syntax heavy and does not require as much in-depth knowledge in JS as React360. May be friendlier to those new to web development.

*Which one should a web developer interested in VR and AR use?*
While OchemXR.com uses a bit of both, most developers choose to use WebXR and others choose to use React360. But both are a means to an end to support XR experiences on the web.

**An oChemXR AR experience**
 
> ![](oChemXrMoleculeModelGif.gif)

**An oChemXR VR experience**
_Placeholder for oChemXR VR experience VR gif_
## 1.1. Overview 


**But...why? VR's dead.**
I LOVE Virtual Reality and Augmented Reality. I just wish more people saw the benefit beyond games (though don't get me wrong- I do love me some BeatSaber gaming seshes.) The applications are exciting and endless...
- AR-assisted surgeries
- molecular and protein visualization for designing new medications
- walking clients throuch 3D architectural designs before their building's even built
- etc, etc, etc... 

I also want to be a WebDev when I graduate. Just sucks I didn't realize it until senior year of my Chem degree at UCSB. With it being too late to switch to the CompSci major, I'm teaching myself how to program virtual reality experiences and fullstack websites. 

**Cool story bro. But I didn't need to read your whole autobiography. What does this program do?** 
Well... it explores the benefits and drawbacks of utilizing Facebook's framework, React360. It also demonstrates how XR platforms on the web may serve as a great alternative (but not replacement) for convential webpages.

**Why web? Why not just use Unity or UnrealEngine?**
Don't get me wrong, 3D game engines like Unity and UnrealEngine are GREAT. They're powerful and the go-to for designing XR games and experiences. 

XR websites like oChemXR.com will NEVER replace downloadable apps. The success of the Apple App Store, Oculus Store, Steam Marketplace, and Google Play Store have all shown that even after the .com boom, downloadable apps will always have their place in consumer technologies for years to come.

But browser-based devices like the ChromeBook and popular web-apps like Google Docs, Youtube, Facebook, and Twitter showcase the value in webapps.

For downloadable VR apps, time-to-download/install and cost are 2 major barriers-to-entry holding back VR from going mainstream. Whether its a psychological or physical barrier (think data caps/limited local storage), the time-to-download can stop a potential end-user from trying out your app. Not to mention the cost of buying a $1000 VR-capable PC PLUS a $400 VR/AR headset can be too overwhelming of an investment for some (at least, it sure is for my broke, college-student self.)

Luckily, recent stand-alone VR headsets like the Oculus Quest at $400 and AR headsets like the Hololens 2 at $3500 (yikes) cut out the cost of a PC.

But that still leaves time-to-download/install as a barrier-to-entry for downloadable apps. Meanwhile, websites are immediately accessible to the user. Plus, updates can be pushed instantly. 

Websites can also be designed to be cross-platform. For example, OChemXr.com can be opened in any browswer, from the Oculus VR browser on your shiny, new Oculus Quest... to Mobile Chrome on your smartphone. 




## 1.2. Table of Contents
<!-- TOC -->
1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
<!-- /TOC -->
## 1.3. Usage

> See below

### 1.3.1. How to run this code
1. Make sure you have Node installed for the npm commands you will run in step 4. (For installation, see https://nodejs.org/en/)
2. Make sure MongoDB is running locally (For installation and running MongoDB, see https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/#run-mongodb)
3. Clone this repo
4. Open terminal in the cloned folder,
   - To install dependencies, run ```  npm install  ```
   - To run MongoDB, ``` mongod --config /usr/local/etc/mongod.conf ``` (run in a 2nd terminal tab/window)
   - To run this app for development, run ```  npm run dev  ```
5. Open [localhost:8081](http://localhost:8081/) in the browser

### 1.3.2. API endpoints
- `GET ______` 
  - returns data from entry with specified id
- `POST ________` 
  - pushes a new entry to the database
- `PUT _______`
  - edits entry 
- `DELETE ______` 
  - removes entry with specified id from database


### 1.3.3. Requirements
- Node 6.13.0
These dependencies/libraries/frameworks will install in your node_modules folder when you "npm install"
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



