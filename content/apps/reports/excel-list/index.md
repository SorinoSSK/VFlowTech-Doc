---
title: "Excel"
description: ""
date: 2021-02-21T14:19:04+08:00
lastmod: 2021-02-21T14:19:04+08:00
draft: false
images: []
menu:
  apps:
    parent: "reports"
weight: 11060
toc: true
---

## Introduction
Excel Feature helps us to download excel report based on the selected sensors and time interval.

{{< img-simple src="excel-home.png" alt="Excel home icon" class="border-0 rounded-circle" >}}

Excel contains 5 sections i.e

1. [Select parameters](#select-parameter)
2. [Select range](#select-range)
3. [File type](#file-type)
4. [Sheet preferences](#select-preferences)
5. [Email](#email)

## Select parameters

In select paramenter section, we can select sensors from the project tree.

{{< img-simple src="select-parameter.png" alt="Selected parameter icon" class="border-0 rounded-circle" >}}

## Select range

In select range section, we can add start date(From) and end date(To) for getting the data for particular time interval.

{{< img-simple src="select-range.png" alt="Selected range icon" class="border-0 rounded-circle" >}}

## File type

In file type section, we have to select the type of file in which we want to download the file. Currently only one option is available `XLSX`, other options will come very soon i.e XLS, PDF, and CSV.

{{< img-simple src="file-type.png" alt="Selected range icon" class="border-0 rounded-circle" >}}

## Sheet Preferences

In sheet preference section, we have select the sheet preference as how the sensor data will be visible in the excel sheets. Currently only one option is available `Create multiple sheets by Project.Gateway name` (In this we get the excel with separate sheet as per the gateways. Suppose we selected 2 sensors one is from `Windy Heights/Building Red/Apt Red 11/Energy Mtr Red 11` and other is `Mukesh/LDR/LDR`, so we get 2 different sheets in the excel as per gateway name i.e `Building Red` and `Mukesh`, both sheets contains particular data for the selected sensor.

Other preferences will be coming soon i.e `Merge into a single sheet with one timestamp column` and `Merge into a single sheet with multiple timestamp columns by Project.Gateway name`.

{{< img-simple src="select-preferences.png" alt="Select preference icon" class="border-0 rounded-circle" >}}

## Email

In email section, we can add email where user want to send the report.

{{< img-simple src="email.png" alt="Email icon" class="border-0 rounded-circle" >}}

After completing all the steps, click on download button to download the report and also email will be sent to the email id which is added in email section.
