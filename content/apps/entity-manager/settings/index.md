---
title: "Alert Rules"
description: ""
date: 2021-02-21T14:06:32+08:00
lastmod: 2021-02-21T14:06:32+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3090
toc: true
---

## Introduction

<p style="text-align: justify;">
Alert rules is a function that allows the creation of rules to send notification to a person. Users can set these rules to send an email, sms or whatsapp message when certain conditions are met. For instance, if the water in a pipe flows faster than a certain amount per minute, a notification will be sent out.
</p>

<p style="text-align: justify;">
When an alert rules is created with sensor types, the conditions of the alert rule will be applied to all the sensors within the particular sensor type. 
</p>

<p style="text-align: justify;">
However, if the alert rules is created with sensors, the alert rule is applied only to the particular sensor. 
</p>

<p style="text-align: justify;">
We can access settings tab from the sidebar to create an alert rule.
</p>

{{< img-simple src="setting-btn-select.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
The alert rules tab contain a list of rules along with their name (Rule name), the date it was created (Created at), severity, alert actions, status, and action buttons.
</p>

{{< img-simple src="alert-rule-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

## Creating an Alert rule

<p style="text-align: justify;">
To create an alert rule, we will click on the <b>Add Rules</b> button.
</p>

{{< img-simple src="add-alert-rule-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on <b>Add Rules</b> button will open a modal. The add alert rule modal contains 3 sub sections: Details, Conditions, and Actions.
</p>

{{< img-simple src="add-alert-rule-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we have to enter the name of the alert rule, rule severity (Low, medium, or high), and the message.
</p>

{{< img-simple src="add-alert-rule-2-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the next section named Conditions, there are 2 tabs: policy and grouping.
</p>

<p style="text-align: justify;">
In the policy tab, we can select the sensor or sensor type and the parameters of the particular sensor or sensor type. In the parameter selection, we have 3 options, e.g.
</p>

1. Send an alert when data is outside the bound range. (In this section, we define the parameter's upper and lower bounds.)
2. Send an alert if the data exceeds the upper limit. (In this we define the upper value for the parameter).
3. Send an alert if the data falls below the lower threshold. (In this, we define the lower value for the parameter).

<p style="text-align: justify;">
The alert rule will only be activated when conditions set in the parameter selection have been met.
</p>

After adding the policy, click on the <b>Next</b> button.

{{< img-simple src="add-alert-rule-2-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the grouping tab, we can define the time interval of a notification that will be sent when the conditions are met. For instance, if the room temperature exceeds 40 degrees Celcius, a notification will be sent every minute.
</p>

<p style="text-align: justify;">
Click on <b>Done</b> at the top right corner, then click on <b>Next</b> button at the bottom right corner after setting the values in the grouping tab.
</p>

{{< img-simple src="add-alert-rule-3-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the last section named Actions, there are 2 tabs: Media and Recipients. 
</p>

<p style="text-align: justify;">
In the Media tab, we can select how we want the alerts to be sent. E.g. SMS, email, or whatsapp. 
</p>

<p style="text-align: justify;">
After selecting the media, click on <b>Next</b> button, which is at the top right corner.
</p>

{{< img-simple src="add-alert-rule-3-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the Recipients tab, we can add phone numbers or emails for alert rules to be sent to. 
</p>

<p style="text-align: justify;">
Click on <b>Done</b> button at the top right corner and then click on <b>Save</b> button to add the alert rule after the recipients have been added. 
</p>

## Editing a Alert rule

{{< img-simple src="edit-modal-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on edit alert rule button will open up a modal. The modal contains 3 sub sections: details, conditions, and actions.
</p>

{{< img-simple src="edit-alert-rule-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we can modify the name of the alert rule, rule severity (Low, medium, or high), and the message.
</p>

{{< img-simple src="edit-alert-rule-2-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

{{< img-simple src="edit-alert-rule-2-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to change the policy or grouping interval of the alert rule, we have to access the second section, condition, where we can modify the parameter's condition and the time interval for the alerts.
</p>

{{< img-simple src="edit-alert-rule-3-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}
{{< img-simple src="edit-alert-rule-3-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to modify the media or recipients, we have to access the third section, actions, where we can add, edit or remove media and recipients. 
</p>

<p style="text-align: justify;">
After entering the details and clicking on the save button, the modification on the alert rule will be saved.
</p>

## Deleting a Alert rule

{{< img-simple src="delete-modal-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on the delete alert rule button will open up a confirmation modal.
</p>

{{< img-simple src="delete-modal.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we click on <b>yes</b>, the specific alert rule will be deleted.
</p>