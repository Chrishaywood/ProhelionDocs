---
title: ArrowPoint Android
tags: [getting_started, formatting, content_types]
keywords: pages, authoring, exclusion, frontmatter
last_updated: July 16, 2016
summary: "The ArrowPoint for Android Solution is an Android App designed to receive and display telemetry information from an WiFi access point in real time. It is a very useful tool in a race environment as every team member can have a copy installed on their own phone or tablet and get instant insights in to the performance of the vehicle."
sidebar: mydoc_sidebar
permalink: mydoc_androidTablet.html
folder: mydoc
---

The ArrowPoint for Android Solution is an Android App designed to receive and display telemetry information from an WiFi access point in real time. It is a very useful tool in a race environment as every team member can have a copy installed on their own phone or tablet and get instant insights in to the performance of the vehicle.

{% include image.html file="android_dashboard.png" url="http://jekyllrb.com" alt="android_dashboard" caption="Example of the Arrowpoint Dashboard" %}

The out of the box implementation is designed for use in Solar or Electric racing cars that use technology from [Prohelion](http://Prohelion.com) or [Tritium](http://Tritium.com). This solution was originally developed by [TeamArrow](http://www.teamarrow.com.au/) and has been used in racing environments since 2015. [TeamArrow](http://www.teamarrow.com.au/) continue to use this application both as the in car dashboard as well as a solution for the entire fleet to communicate and monitor the car.

Examples of the software in use can be seen here - [https://www.youtube.com/watch?reload=9&v=lWkXEb8v1tk](https://www.youtube.com/watch?reload=9&v=lWkXEb8v1tk)

If you are interested in contributing to the solution, please see our Contribution File.

## Features
The application provides

A Driver Dashboard showing all key information for the driver (we use this as our in car dashboard in the Arrow1)

A Solar Energy Dashboard showing key solar data and battery information

Customisable Alerts that can be used to alert the team or driver to systems going out of range or offline

Private Messaging for inter-fleet communications that does not require the radio

A Graphing Dashboard that can be used to graph information over time

The application is compatible with

Prohelion Battery Packs

Tritium WaveSculpters

Tritium BMUs and CMUs

The Wifi connection should be broadcasting CANbus data using the Tritium CANbus identifiers.

Any issues please or question, please raise them on our GitHub account at [https://github.com/Prohelion/ArrowPoint-Android](https://github.com/Prohelion/ArrowPoint-Android)

## Installation on the Tablet or Phone
Installation of the ArrowPoint App requires the installation of the Android Studio tools, we would suggest version 3.1.4 or above. Place the tablet or phone that you wish to install the application on to in to development mode by following the [Development Mode instructions on the android web site](https://developer.android.com/studio/debug/dev-options). Connect a USB cable from the PC where you are running Android Studio to the tablet or phone and then run the application on the tablet from the Development Studio. Once the application has been installed it will appear as an arrow icon and can be run without the PC attached via the cable.

## Running the Solution
The tablet will look to get CANBus information from a WiFi Connection point. TeamArrow has used this solution in the past by running three Wifi Access points, one in the solar car and one in the chase and lead car, allowing the tablet to connect to whichever one has the strongest signal. Because the solar car is typically made out of carbon fibre, which does a great job of blocking Wifi signals, we would suggest taking care where you install the Wifi access points to maximise the stability of the connection in the vehicle.

## Compilation and Development
If you are planning to contribute to the development of this tool, please see our [Contribution File]9https://github.com/Prohelion/ArrowPoint-Android/blob/master/CONTRIBUTING.md) on GitHub.

As mentioned above, compilation and development requires [Android Studio](https://developer.android.com/studio).

## Known Issues
Not all Android hardware is able to receive UDP packets and typically this capability is only available in mid tier to high tier Android tablets and Phone. TeamArrow have been racing with this solution for a number of years and we have typically found that Samsung products provide the most reliability in this space. It is worth checking that your tablet or phone can handle UDP broadcast traffic before attempting to use this application.

This applications receives 100's of CANbus packets per second and as such puts significant strain on the battery, also the screen runs all the time. We have typically found that we need a tablet per sector when running an event like World Solar Challenge. TeamArrow carries multiple tablets in the fleet and always has a few on charge at any time.

## Issues or Suggestions
If you have any issues with the code or discover bugs then we would encourage you to log them on the issues page here [https://github.com/Prohelion/ArrowPoint-Android/issues](https://github.com/Prohelion/ArrowPoint-Android/issues) or have a go at fixing them and then send us a pull request with details of what you have done. If you are fixing a bug, please log it as per the [Contribution File](https://github.com/Prohelion/ArrowPoint-Android/blob/master/CONTRIBUTING.md) instructions so that we have an idea on what you are attempting to do. Also check out the Software Troubleshooting page for more information.

{% include links.html %}