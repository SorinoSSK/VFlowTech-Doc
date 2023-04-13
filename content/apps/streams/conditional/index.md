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

<p style="text-align: justify;">
Conditional node can be used to divert a pipeline execution by using conditional logic ( <b>Javascript code</b> ).
</p>

<p style="text-align: justify;">
We can write javascript code in this node and compare event values to perform logical comparison. For the comparison to occur, we will need to write a Javascipt function with <b>condition</b> as the name together with the logic in the code field of the node. This node will have 2 output port for <b>true</b> and <b>false</b> conditions.
</p>

### Action Fields

#### Name
Name field can be used to give a custom name to the node.

#### Code
<p style="text-align: justify;">
We can write a function named `condition` in this field and we should receive a boolean value after it is executed.
The condition function will receive the <b>payload</b> as function parameters which can be used to perform logical operations.
</p>

<p style="text-align: justify;">
The following example shows the implementation of a condition function. The example compares temperature using payload.
</p>

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