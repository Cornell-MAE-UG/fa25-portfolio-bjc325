---
layout: project
title: Lifting a Weight
description: Class project with Graphs
technologies: [MATLAB, python]
image: /assets/images/Project1.jpg
---


As part of a class project we were given a 2D design space of 150cm x 50cm, a rigid bar of a fixed length that we could choose, 3 pin supports, and a linear actuator. The task was to design a frame/mechanism to lift the maximum possible weight to the highest possible height. We assumed that all the components are rigid.

This is how I solved the problem:

First I had to decide what kind of actuator I wanted to use. I decided to use the RSX linear actuator because it provides the highest max force, allowing it to provide the most moment, and it also has the highest stroke length allowing it to potentially push the weight up farther. I analyzed conceptually where the best place to put the linear actuator was on the bar in order to provide the most moment. I found that no matter where on the bar we placed the actuator, the angle between the actuator's line of action and the rod would be the same, so in order to maximize the moment provided by the linear actuator I decided to place it at the end of the rod.