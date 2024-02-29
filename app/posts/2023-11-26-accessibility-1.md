---
title: Accessibility of web integration options
description: This testing used a technical proof-of-concept app rather than a Figma prototype. The app was loaded onto GDS devices that were handed to participants. We wanted to explore the differences between three methods of integrating GOV.UK web content.
date: 2023-11-26
screenshots:
  items:
    - text: "View selection screen"
      src: /assistive-tech-1/01-View-selection.png
    - text: "Web integration option 1: Web view with injected Javascript"
      src: /assistive-tech-1/02-Web-view.png
    - text: "Web integration option 2: Android Custom tab / iOS Safari view controller"
      src: /assistive-tech-1/03-Safari-view-controller.png
    - text: "Web integration option 3: System browser"
      src: /assistive-tech-1/04-Browser-view.png
---

## Research objectives 

1. Understand user experience of web integration options when using assistive technology
2. Identify bugs, pain points or risks within the different integration options
3. Feed into report to support the decision for an integration option for MVP

## What we did

- 1 Round of in-person UR
- 7 participants
- Accessibility testing 3 web integration options: Web wrapped, Custom tab and Browser push

## Summary of insights

### How people use assistive technology on their mobile phones
Participants have learned to use assistive technology on their phone mainly through trial and error or with support from others, so all used slightly different techniques for using their phones. 
This method of learning meant some participants weren’t confident with their use of assistive technology.

### Organic learning networks
When participants had become more confident with the technology they talked about sharing their experience and helping other people to learn through their social networks.
This means we need to consider that users will be using assistive technology in ways they know or have been taught by their community, rather than the most technically efficient methods. The app needs to support these methods or work arounds. 

### Learning to use their mobile phones
Participants talked about needing to practise to learn to use their assistive technology or specific apps. If apps were inaccessible, they needed to get help from others or find a replacement app.
This shows the need for two things: 
1. The app needs to be easy to use and learn to reduce the effort of learning
2. The app proposition needs to be clear so that users choose to invest time in this way

### Using web views
Web views were easier for users to navigate to back to the home page from and presented fewer usability issues than the other integration options for users within this sample.
Some participants struggled more to navigate back from the view controller or the browser options and got lost in the header and footer content.

## What we showed users

We ran the technical proof of concept app on GDS devices and handed them to users in the session. We used a Samsung Galaxy A32 for Android users and an iPhone 11 for iOS users. The app included three different web views of the ‘View of share your driving licence’ service.
