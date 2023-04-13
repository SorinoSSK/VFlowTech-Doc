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

<p style="text-align: justify;">
Transform node can be used to transform any event payload using  <b>Javascript code</b>.
</p>

<p style="text-align: justify;">
Moreover, we can perform calculation using Javascript code in this node and update the payload with the calculated value. To do so, we must return javascript output as a payload output through the implemention of the `transform` function.
</p>

### Action Fields

#### Name
<p style="text-align: justify;">
Name field can be used to give a custom name to the node.
</p>

#### Code
<p style="text-align: justify;">
In this field, we will write a function named <b>transform</b> to return an updated payload value. The transform function will then receive the payload as function parameter which can be used to perform calculation and update the payload.
</p>

The following is an example of the function implementation. In this example, we are updating the payload, temperature to be in fahrenheit.

```javascript
function transform(payload) {
  let temperature = payload.temperature;
  let fahrenheit_temp = (temperature * 9/5) + 32;
  payload["fahrenheit_temp"] = fahrenheit_temp;
  return payload;
}
```