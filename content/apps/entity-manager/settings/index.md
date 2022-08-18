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

Alert rules are the rules that are sent to the email ids or phone numbers if the specific condition is matched for the particular sensor or sensor type parameters. 

When we create alert rules in sensor types, the alert rule is applied to all the sensors that are part of the particular sensor type. 

When we create alert rules in sensors, the alert rule is applied to the particular sensor. 

To create the alert rules, we have to go to the settings tab from the side bar.

{{< img-simple src="setting-btn-select.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Then we have to select the particular project for which we have to create the alert rules.

{{< img-simple src="select-project.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

The Alert rules list contains name of the rule(Rule name), date it was created(Created at), severity, alert actions, status, and action buttons

{{< img-simple src="alert-rule-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

## Creating an Alert rule

Now to create an alert rule, we click on the Add rule button.

{{< img-simple src="add-alert-rule-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open a modal. The Add alert rule modal contains three sections: Details, Conditions, and Actions.

{{< img-simple src="add-alert-rule-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named "Details," we have to add the alert rule name, rule severity(Low, medium, or high) and the message.

{{< img-simple src="add-alert-rule-2-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the next section named Conditions, there are two tabs: policy and grouping.

In the policy tab, we have to select the sensor or sensor type and then select the parameters of the particular sensor or sensor type. In the parameter sections, we have 3 options, i.e.

1. Send an alert when data is outside the bound range.(In this section, we define the parameter's upper and lower bounds.)
2. Send an alert if the data exceeds the upper limit.(In this we define the upper value for the parameter).
3. Send an alert if the data falls below the lower threshold. (In this, we define the lower value for the parameter).

If the condition is matched with the selected dropdown, then the alert rule will be fired.

After adding the policy, click on the Next button.

{{< img-simple src="add-alert-rule-2-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the grouping tab, we can fire alerts in the groups at a particular time interval. 

After adding the grouping time interval, first click on Done at the top right corner, then click on the Next button at the bottom right corner.

{{< img-simple src="add-alert-rule-3-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the last section named Actions, there are two tabs: Media and Recipients. 

In the Media tab, we can select how we want to send the alerts via SMS or email. 

After selecting the media, click on the Next button, which is at the top right corner.

{{< img-simple src="add-alert-rule-3-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the Recipients tab, we can add phone numbers or email IDs where the alert rules will be sent. 

After adding the recipients, click on the Done button at the top right corner and then click on the Save button to add the alert rule. 

This is how we create alert rules.

## Editing a Alert rule

{{< img-simple src="edit-modal-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on edit alert rule button will open up a modal. The modal contains three sections: details, conditions, and actions.

{{< img-simple src="edit-alert-rule-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named "Details," we can edit the alert rule name, rule severity(Low, medium, or high), and the message.

{{< img-simple src="edit-alert-rule-2-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

{{< img-simple src="edit-alert-rule-2-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we want to change the policy or grouping interval for the alert rule, then we have to click on the second section, i.e., condition, and then we can edit the parameters condition and also the time interval for grouping alerts.

{{< img-simple src="edit-alert-rule-3-1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}
{{< img-simple src="edit-alert-rule-3-2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

And if we want to edit the media or recipients, then we have to click on the third section, i.e., actions, and then we can add or remove the media and recipients. 

After entering the details, clicking on the save button will edit the alert rule for us.

## Deleting a Alert rule

{{< img-simple src="delete-modal-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on the delete alert rule button will open up a confirm modal.

{{< img-simple src="delete-modal.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we click on yes, then the specific alert rule will be deleted.
