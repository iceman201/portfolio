---
layout: post
title: SCADAFarm
description: A project management tool based around tracking the installation of cables
image:
---

![test image]({{ site.url | absolute_path}}/assets/images/SCADAFarm/Scadafarm-iphone1.png){:.center height="50%" width="50%"}

### Introduction
SCADAfarm is a modular, integrated control and monitoring system that allows farmers to control, monitor, and data-log key aspects of their farm's operation. It is designed to work with the farm's existing control systems, such as irrigation and pump controllers. The app allows you to remotely control and monitor your farm’s irrigation system.

![test image]({{ site.url | absolute_path}}/assets/images/SCADAFarm/Scadafarm-iphone2.png){:.center height="50%" width="50%"}

### Development
SCADAfarm is an iOS Application made by McKay Software, as an employee at the time I was maintaining and adding new features. Some of the difficulties were to be careful with memory management when drawing the pivot animation image on the map view and thread management of loading big amount information from server.

- Swift 2.1
- Framework involved:
  - SVProgressHUD
  - Mapbox
  - Alamofire
  - Core Graphic
  - Core Animation.
- Device support:
  - iPhone
  - iPad
- Platform:
  - Mobile
  - Website
