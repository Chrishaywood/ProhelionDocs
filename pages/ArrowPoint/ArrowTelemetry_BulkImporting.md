---
title: ArrowPoint Telemetry - BulkImporting
tags: [ArrowPoint, Telemetry, BulkImporting]
keywords: ArrowPoint, Telemetry, BulkImporting
last_updated: November 22, 2019
summary:
sidebar: mydoc_sidebar
permalink: ArrowTelemetry_BulkImporting.html
folder: ArrowPoint
---

The system provides the ability for CANbus files that have been recorded by either the [ArrowPoint CANbus Tools](ArrowCANbus_Overview.html) or the Tritium Can Logger to be bulk loaded in to the telemetry system.

This is particularly useful if you want to analyse previously recorded CANbus files in the reporting tools such as Splunk.  An example canlog.csv file can be found in the root directory of the source code for the Telemetry system.

To load a file place it in the 

```
[Install Dir]/canbus_bulkloaddirectory.
```

{% include links.html %}