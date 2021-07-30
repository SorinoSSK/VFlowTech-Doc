---
title: "Download Dashboard Report"
description: ""
date: 2021-02-21T14:13:02+08:00
lastmod: 2021-02-21T14:13:02+08:00
draft: false
images: []
menu:
  apps:
    parent: "dashboards"
weight: 5080
toc: true
---

User can download a dashboard report in CSV, XLSX, PDF format. <br/>

For that click on the Download Report action present at the bottom of the Dashboard sidebar as shown below. <br/>
{{< img-simple src="download-report-action" alt="Dashboards app" class="border-0 rounded-circle" >}}

On clicking a button, download report modal will be opened as shown below.
{{< img-simple src="download-report-modal" alt="Dashboards app" class="border-0 rounded-circle" >}}

To download a report, there are four steps

* **Select Parameters:**
In this user can select one or more sensor parameters of which user wants to generate a report. <br/>
Let's select sensor parameters as shown below.
{{< img-simple src="select-parameters" alt="Dashboards app" class="border-0 rounded-circle" >}}

* **Select Range:**
Here user can select range between which user wants to generate a report. <br/>
Let's select a range from 5th June to 15th June as shown below.
{{< img-simple src="select-range" alt="Dashboards app" class="border-0 rounded-circle" >}}

* **File Type:**
User can select what type of file format, user wants to generate a report. <br/>
Currently user can generate a report in XLSX format only.
{{< img-simple src="select-file-type" alt="Dashboards app" class="border-0 rounded-circle" >}}

* **Sheet Preferences:**
This option will be visible only when user selects XLSX format in file type section. <br/>
Here user can configure how XLSX sheets should be generated based on selected sensor parameters. <br/>
In the first option, which is the only option available right now. So let's say if three sensor parameters are selected and if all of the sensors are connected to the same gateways, then only one sheet will be generated. If these sensors are connected to two different gateways,then two sheets will be generated.
{{< img-simple src="select-sheet-preferences" alt="Dashboards app" class="border-0 rounded-circle" >}}

* **Email:**
The last step is to enter email where user want to send a report.
{{< img-simple src="select-email" alt="Dashboards app" class="border-0 rounded-circle" >}}

When user is done with these steps, user can click on download button and an email will be sent.
