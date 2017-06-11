---
layout: post
title: Sidewinder
description: A project management tool based around tracking the installation of cables
image:
---

![test image]({{ site.url | absolute_path}}/assets/images/Sidewinder/Sidewinder.png){:.center}

### Introduction
Sidewinder is a project management tool based around tracking the installation of cables. Sidewinder provides real-time traceability of work done on a cable installation project, as well as a status dashboard to allow project managers and lead contractors to quickly determine the progress being made and remaining workloads.

### Development
Sidewinder is an iOS Application made by McKay Software, as an employee at the time I was doing the new version development and maintaining. Since Sidewinder needs to be able work offline. We are not only fetching data from RESTful API and also need to store as much data as possible into local Realm database. After user did change on offline mode it will automatically sync data to the server to keep consistency.

- Swift 2.1
- Framework involved:
  - Realm
  - SVProgressHUD
  - SwiftHTTP(replaced by Alamofire in latest version)
  - Core Animation.
- Device support:
  - iPhone
  - iPad
