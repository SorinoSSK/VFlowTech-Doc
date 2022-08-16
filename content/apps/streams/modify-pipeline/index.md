---
title: "Modify Pipeline"
description: ""
date: 2022-08-12T16:42:02+05:30
lastmod: 2022-08-12T16:42:02+05:30
draft: false    
menu:
  apps:
    parent: "streams"
weight: 1009
images: []
---

When a new project is created, it has default pipeline in it as shown below.

{{< img-simple src="streams-default-pip.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

As we can see in the above image that we have 2 nodes (ie. init and save) connected to each other.
We will get into more details about how each action works, in above pipeline the event that comes will save saved to DB after doing parameter mapping.

Left side of the workarea show the list of nodes that can used to create pipelines.
On the right hand side panel we show the selected node fields which can be editied by user. 


Following is a small demo of how pipeline can be created.

{{< img-simple src="modify-pipeline.gif" alt="Role Manager app" class="border-0 rounded-circle" >}}