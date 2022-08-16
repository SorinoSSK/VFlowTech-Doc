---
title: "Init"
description: ""
date: 2022-08-12T17:33:54+05:30
lastmod: 2022-08-12T17:33:54+05:30
draft: false
menu:
  apps:
    parent: "streams"
weight: 1010
images: []
---

Init node acts as starting point of pipeline creation. When a pipeline is executed, init node is the action where the event is first sent and then
it traverse further down the pipeline.

It is mandatory to have init node in the pipeline and it cannot be deleted.
