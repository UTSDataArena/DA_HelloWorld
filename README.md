# "Hello World" Data Arena + Unreal Engine

#### Our template project to help you develop for the DA
Welcome to our *Hello World* project. This Unreal Engine project is designed as a template to help you develop for the UTS Data Arena. For most purposes, running Unreal Engine projects in the Data Arena is plug-and-play without any specific build requirements besides version.

> 👉 We have locked off support for **Unreal Engine 4.25** projects (as of July 2021). We are currently working on more recent versions of the engine but for now require projects built in **4.25.4** or older.

In this simple project, you're able to navigate a `SpaceMouseCamera` Camera Actor and highlight, pickup, move and drop objects with the `TrackerCursor` class. This project and the DA Assets plugin (see below) were developed from technologies developed for our Unreal Engine debut [Cozy Living Room](https://dataarena.net/projects/cozy-living-room) project.

## 🔌 DA Assets Plugin
This project includes our [DA Assets plugin](https://github.com/UTSDataArena/DA_Assets) to let you easily interface with our input devices at the Data Arena. For more information and to start developing, take a look at our plugin documentation (link above).

## ⚡️ Setup and Run
To run our *Hello World* project, download this repo by either clicking *Code* → *Download ZIP* (above) or cloning this repository if you're familiar with Git, and open the `DA_HelloWorld.uproject` file in Unreal Engine 4.25.4 or earlier. You should be able to run this project on either Windows, macOS or Linux.

The included `SpaceMouseCamera` and `TrackerCursor` classes include a ***Use VRPN Input*** switch (accessible in the details panel). Leave this disabled (off) as you develop outside the Data Arena environment. For more information on this option, see our [DA Assets](https://github.com/UTSDataArena/DA_Assets) documentation.

## ✉️  Get in touch
For more information take a look at the [UTS Data Arena](https://dataarena.net) website and [get it touch](https://dataarena.net/about#contact) with us about your first Data Arena project. We'd love to hear about what you've got planned with Unreal Engine and how we can help make it happen.
