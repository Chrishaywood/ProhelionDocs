---
title: ArrowPoint Android
tags: [ArrowPoint, Dashboard, Telemetry]
keywords: ArrowPoint, Dashboard, Telemetry
last_updated: November 22, 2019
summary:
sidebar: mydoc_sidebar
permalink: ArrowTelemetry_Overview.html
folder: ArrowPoint
---

The ArrowPoint Telemetry Solution is designed to provide telemetry capture and management information for managing a race car.

The out of the box implementation is designed for use in Solar or Electric racing cars that use technology from Prohelion or Tritium. This solution was originally developed by TeamArrow and has been used in racing environments since 2013. TeamArrow continue to use this application as the heart of its telemetry and strategy management solutions.

The solution captures and stores all telemetry data in a race environment and has been used to capture over 60,000,000 data points in previous events and testing and can manage, track and store around 400 data points a second when running on a i7 laptop. It provides reporting (via Splunk) across full data sets via a web interface and allows teams to build and track massive data sets via dashboards and dynamically modifiable searches.

{% include image.html file="telemetry_analysis.png" alt="telemetry_analysis" caption="Example of the Arrowpoint Dashboard" %}

The ArrowPoint-Telemetry system is very light weight (considering what it is doing!) and TeamArrow have historically run it on a single CPU laptop, which we tuck on the seat in the chase car or can be run in the cloud (we use Amazon EC2) when coupled with the ArrowPoint-Tablet for data relay.

Examples of the software in use can be seen here - https://www.youtube.com/watch?reload=9&v=lWkXEb8v1tk

If you are interested in contributing to the solution, please see our contribution file here
https://github.com/Prohelion/ArrowPoint-Telemetry/blob/master/CONTRIBUTING.md

For the full feature list see the Telemetry System Features page, but at a high level the application provides

CANbus data capture and reporting either directly off the car, via the ArrowPoint-Tablet or a JSON stream

Alerting via a visual signals (USB light), when key data points go out of range

Storage of CANbus data in a relational data set for later reporting against very large datasets

Relaying of data to other ArrowPoint-Telemetry instances

Integration with SPLUNK for larger scale data capture and real time reporting

Mechanisms to visualise your position and strategy in Google Earth

The application is compatible with

Prohelion Battery Packs

Tritium WaveSculpters

Tritium BMUs and CMUs

Any issues please or question, please raise them on our GitHub account at https://github.com/Prohelion/ArrowPoint-Telemetry or see the Software Troubleshooting page.

{% include links.html %}