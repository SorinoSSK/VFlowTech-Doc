---
title: "Add Hash"
description: ""
date: 2021-02-21T14:19:36+08:00
lastmod: 2021-02-21T14:19:36+08:00
draft: false
images: []
menu:
  apps:
    parent: "digital-twin"
weight: 10060
toc: true
---

## Introduction
{{< img-simple src="digital-twin-hash-icon.png" alt="Hash icon" class="border-0 rounded-circle" >}}

Hash is used to map sensor parameters data to other editor elements like images, shapes, symbols etc.

We can add hash to the editor using above icon. Once it is added, a sidebar will open on the right side where we can choose sensor paramenters for mapping and also we can change the visual settings like Text Format.

{{< img-simple src="digital-twin-hash-settings.png" alt="Hash settings" class="border-0 rounded-circle" >}}

As we can see in the above image, initially hash has no data so it shows `# unit`.

To select sensor parameters, click on `Choose Data` button.

Once clicked, we will see a tree like projects structure where we can select sensor parameters from any of the projects.

Click on `Apply Changes` button to save your selection.

{{< img-simple src="digital-twin-hash-tree.png" alt="Choose Hash Data" class="border-0 rounded-circle" >}}

Once sensor parameters are selected, we can see the details in the sidebar like which sensor parameter we have selected and from which project (refer below image).

Now as we have mapped data, so we can see it's value with unit in the editor. Here we have set `unit` to `V`.

{{< img-simple src="hash-selected-sensor.png" alt="Selected Hash Data" class="border-0 rounded-circle" >}}

Here also we can perform operations like `delete, drag, resize, rotate` and can use `On Board Alignment` options in the same way as we do in images.

Once our changes are done, we can save it via `Apply Changes` button on the bottom of the sidebar.