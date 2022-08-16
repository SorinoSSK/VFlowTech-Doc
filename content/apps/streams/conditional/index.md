---
title: "Conditional"
description: ""
date: 2022-08-13T08:32:06+05:30
lastmod: 2022-08-13T08:32:06+05:30
draft: false
menu:
  apps:
    parent: "streams"
weight: 1012
images: []
---

Conditional node can be used to divert the pipeline execution by writing conditional logic (`Javascript code`).

In this node we can write javascript code and compare the event values to do logical comparison.
We need to write a Javascipt function named `condition` with the logic for code field of the node.
This node has 2 output port for `true` and `false` conditions.

### Action Fields

#### Name
Name field can be used to give custom name to the node.

#### Code
In this field we write function named `condition` which should return a boolean value.
Condition function will receive the payload as function parameter which can be done to use logical operations.

Following is how the condition function can be implemented:
Here we are comparing the temperature from payload.

```javascript
function condition(payload) {
  if(payload.temperature > 27) {
    return true;
  }
  else {
    return false;
  }
}
```