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

<p style="text-align: justify;">
When a new project is created, it should have a pipeline created by default as shown below.
</p>

{{< img-simple src="streams-default-pip.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
As we can see from the above image, we have 2 nodes <b>init</b> and <b>save</b> created and are  connected to each other.
</p>

<p style="text-align: justify;">
We will get into more details on how each action works. In the pipeline shown above, events received will be saved to the database after some parameter mapping are completed.
</p>

<p style="text-align: justify;">
The left side of the page display a list of nodes that can used to create a pipeline.
</p>

<p style="text-align: justify;">
On the right hand side of the page, we see and modify information of the selected node fields. 
</p>

The following video image is a demo of how a pipeline can be created.

{{< img-simple src="modify-pipeline.gif" alt="Role Manager app" class="border-0 rounded-circle" >}}