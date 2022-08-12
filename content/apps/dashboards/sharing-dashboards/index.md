---
title: "Sharing Dashboard"
description: ""
date: 2021-02-21T14:13:02+08:00
lastmod: 2021-02-21T14:13:02+08:00
draft: false
images: []
menu:
  apps:
    parent: "dashboards"
weight: 5050
toc: true
---

A Dashboard can be shared to others by a link. <br/>
Dashboard can be shared in two different ways <br/>

* Using Link
* Using CockPit

### 1. Using link

* Public: Can be viewed with link only.
* Private Can be viewed with link and password of the dashboard.

To share a dashboard, click on the shared icon at top right corner of the dashboard header.
{{< img-simple src="share.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

Once we click on share button, Sidebar will be apear on the right side as sown below. <br/>
{{< img-simple src="rightSidebar.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

## Share dashboard as public (Using link)

To share a dashboard as public, select the public radio button and then click on Generate Link. <br/>
{{< img-simple src="sharePublic.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
{{< img-simple src="sharedPublic.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

## Share dashboard as private (Using link)

To share a dashboard as private, click the priave radio button and enter the password which will be needed when someone access the dashboard by a link. <br/>
Then click on Generate Link and dashboard will be exported as a private dashboard. <br/>
{{< img-simple src="sharePrivate.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
{{< img-simple src="sharedPrivate.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
We can then share the link and password of the private dashboard.
When someone opens the private dashboard with the link, first it will be prompt with the modal to enter password.
{{< img-simple src="passowrdPopUp.PNG" alt="Dashboards app" class="border-0 rounded-circle" >}}
After user enters the password, then they can view the dashboard as shown below
{{< img-simple src="shared.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
If the user forgot the password of the dashboard, then password can be revealed with the help of the MADS application password which user has used to logged in to the application.
{{< img-simple src="passwordVisible.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
On clicking the reveal password, user will have to enter the password and then click on next button, after that password will be visible. <br/>
{{< img-simple src="enterMadsPassword.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
{{< img-simple src="revelPassword.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

## Update shared dashboard access

When the dashboard is already shared as Public or Private, it can be changed to Private or Public respectively. <br/>
If user wants to Change private dashboard to public, then first they have to click on public radio button and then enter the MADS application password as shown below. <br/>
{{< img-simple src="changeAccess.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
Click on the save button, once password is verified, then the dashboard access will be changed to public. <br/>
{{< img-simple src="changeAccessPassword.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
After changing the access of the dashboard, link will be the same, so all users with the link can view the dashboard without any password. <br/>
{{< img-simple src="sharedPublic.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

### 2. Using CockPit
  To share dashboard using CockPit  <br/>
  1. Open CockPit section in Sidebar  <br/>
  {{<img-simple src="usingCockpit.png" alt="Dashboards app" class="border-0 rounded-circle" >}}  <br/>
  2. User can share dashboard with single or multipel email ids <br/>
  Once emails are enterd, Email template will be shown as below, user can modify this template if he/she wants to.<br/>
  After template modification done, click on share button. <br/>
  {{<img-simple src="emailTemplate.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
  Once the Sharing is completed, user can see the list of emails with dashboard was shared <br/>
  {{<img-simple src="sharedEmails.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
  If user wants to revert access of perticular shared user, then user can delte that perticular shared emil id. <br/>
  {{<img-simple src="removeEmail.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  
