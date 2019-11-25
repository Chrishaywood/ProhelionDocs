---
title: ArrowPoint Telemetry - GPS
tags: [ArrowPoint, Telemetry, GPS]
keywords: ArrowPoint, Telemetry, GPS
last_updated: November 22, 2019
summary:
sidebar: mydoc_sidebar
permalink: ArrowTelemetry_GPSIntegration.html
folder: ArrowPoint
---

The Telemetry system can track your current location which can then be displayed on Google Maps.

We us the iPhone app GPS2IP to capture the GPS data and push it to the telemetry system

{% include image.html file="telemetry_GPS.png" alt="telemetry_GPS" caption="Iphone GPS Coordinate example" %}

Prohelion Documentation > GPS Integration > image-20190221-072525.png
The reason we use an iPhone app is simply redundancy and ease of development. The iPhone is typically mounted on the dash of the chase car and connected to the in car Wifi network. It captures GPS data and then transmits it to the Telemetry application which is listening on a socket for the GPS data. The Telemetry application then broadcasts the GPS data as CANbus packets for other devices to receive.

{% include links.html %}