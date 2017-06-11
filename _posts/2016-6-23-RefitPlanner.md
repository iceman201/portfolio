---
layout: post
title: RefitPlanner
description: A mobile data collection App that allows vessel captains, owners and operators to gather information relating to maintenance, refit and repair work specification compilation.

image:

---

![test image]({{ site.url | absolute_path}}/assets/images/RefitPlanner/Refitplanner-iPad.png){:.center height="50%" width="50%" }

### Introduction

Refit Planner is a mobile data collection App that allows vessel captains, owners and operators to gather information relating to maintenance, refit and repair work specification compilation. The mobile nature of the App allows members of the crew to utilize a tablet to answer questions about the various tasks at their location anywhere in the vessel. Pictures can be taken of the work site and related systems/equipment and edited in the App. All collated data will be simultaneously synchronized with the RefitPlanner website when connected.
The App has 2 stages; the first being a registration process, addition of vessel and contact details and the submission of a categorized work-list containing all known tasks for the upcoming refit, repair or maintenance work package. This work list is then submitted to MML for review of categorisation and allocation of a unique numbering system. Stage 2 follows this review where the work list tasks can be accessed individually within the App and a questionnaire completed to allow additional information and pictures relating to each task to be captured and uploaded, via the App, to the website. Further tasks can be added within the App at any time and anything new added will be synched with the website and will therefore allow dynamic update and review.

### Development

Refit Planner is an iOS Application made by McKay Software, as an employee at the time I was involved with the first version of this product and collaborate with my manager. The hardest part of this app is annotation on image upload to parse. Since client wants the user to re-edit the image annotation like Adobe Acrobat in iPad and Website as well. Which means we can’t save the image into Parse server straightaway as image file. By solving this issue myself and my colleague come up with an idea is that we shall store it as image file into Parse directly. However, every single drawing from Core Graphic, we generate a coordinate of each annotation. Inserting the annotation information as a binary set into end of the image file. It’s like exif but it’s not real exif. The reason why I don't insert it into image exif directly is that there was no perfect solution for reading exif in iPad in background thread at that time. This makes easier for web developer to read the file from database.

- Swift 2.3
- Framework involved:
  - Parse
  - Alamofire
  - Core Graphic
  - Core Animation.
- Device support:
  - iPad
- Platform:
  - Mobile
  - Website
