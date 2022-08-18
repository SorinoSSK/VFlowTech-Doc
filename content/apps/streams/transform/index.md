---
title: "Transform"
description: ""
date: 2022-08-13T08:32:06+05:30
lastmod: 2022-08-13T08:32:06+05:30
draft: false
menu:
  apps:
    parent: "streams"
weight: 1013
images: []
---

Transform node can be used to transform the event payload using code(`Javascript code`).

In this node we can do calculation using Javascript code and update the payload.
We should return javascript map as payload output from the implemented `transform` function.

### Action Fields

#### Name
Name field can be used to give custom name to the node.

#### Code
In this field we write function named `transform` which should return updated payload.
Transform function will receive the payload as function parameter which can be used to do calculation and update the payload.

Following is how the transform function can be implemented:
Here we are updating the payload with fahrenheit temperature.

```javascript
function transform(payload) {
  let temperature = payload.temperature;
  let fahrenheit_temp = (temperature * 9/5) + 32;
  payload["fahrenheit_temp"] = fahrenheit_temp;
  return payload;
}
```