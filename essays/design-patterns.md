---
layout: essay
type: essay
title: "Bridging the Gap: Software Development and Creative Media"
# All dates must be YYYY-MM-DD format!
date: 2023-11-24
published: false
labels:
  - Software Engineer
  - Creative Media
---
<img width="500px" class="rounded float-start pe-4" src="https://images.ctfassets.net/cnu0m8re1exe/53lGAXqNnH8FSqx4swl9HS/827016cbd0746e791e28f430ddebd9a4/artisticmind.jpg">

## Introduction

As I've mentioned numerous times in previous essays, I've been exposed to the creative media field, where I've learned to produce videos. Learning video editing taught me "design patterns" that I can apply in my own production. These design patterns, however, are much different to software development design patterns. In creative media, we don't explicitly refer to them as design patterns; instead, they are commonly known as techniques. Examples of such techniques include the rule of thirds, color grading styles, transitions, and typography

## Creative Media vs. Software Development
Creating a visually appealing sequence in video editing is more than just putting clips together. It is a process in which each transition, effect, and element is carefully thought out to create an emotion or deliver a specific message. There are design patterns that an editor would employ to get the desired expression. When producing a professional video, for example, a fade-in and fade-out transition between two clips may be preferable to a zoom-in, zoom-out transition. These design patterns, however, are not the same as software development design patterns.

Design patterns in software development are geared toward reusing solutions to common problems. This is an issue for people working in creative media because recycling techniques may appear contradictory to the artistic expression that this field encourages. In contrast to the structured and rule-based nature of coding, creative media thrives on the unusual and the unexpected.

## Storytelling in Code

In the development of the "Manoa-Melody" application, my team and I used the Presentational Component and Container Component pattern in the design of the "My Profiles" page. This particular page presents user image, biography, and the musical instruments they play, along with the genres that they like. Crucially, it goes beyond the display of the user's information by incorporating changing contents, the events a user has created and the updated profile set up.

The Container Component fetches user data from both the user profiles collection and the events collection. It dictates what data should be presented to the user and handles the data retrieval. This clear separation of concerns allows the Presentational Component to render the received data. It receives the user data, including user image, bio, instruments, genres, and updated event information.

Drawing a parallel to video editing, the application of effects on a clip is similar to the Container Component and Presentational Component pattern. Consider the scenario of color grading in Adobe After Effects—an aspect of video editing that transforms the visual appeal of a clip. In this analogy, the clip itself can be likened to the Container Component, representing the raw footage. The color grade serves as the Presentational Component, responsible for rendering and displaying the visual transformation to the viewer.

## Conclusion

In conclusion, while design patterns in creative media and software development may initially seem worlds apart, they have their similarities. Both fields involve application of patterns to achieve specific objectives, whether in producing a video or developing a software application. The nuanced distinction lies in the nature of these patterns – creative media relies on techniques for artistic expression, such as the rule of thirds and color grading, while software development employs patterns to solve common problems.