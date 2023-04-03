---
title: "Role Manager"
description: ""
date: 2021-02-21T13:41:19+08:00
lastmod: 2021-02-21T13:41:19+08:00
draft: false
images: []
menu:
  apps:
    parent: "role-manager"
weight: 2010
toc: true
---

## Introduction
<p style="text-align: justify;">
Role Manager App helps us to define user roles and manage user-level access control in VFT Energy System apps and actions within those apps.
</p>

<p style="text-align: justify;">
The icon below represents the Role Manager app. Role Manager is the first app you should understand.
</p>

{{< img-simple src="role-manager.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

You can find it in the appbar as shown below.

{{< img-simple src="role-manager-in-appbar.png" alt="Role Manager icon in the appbar" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on this icon will launch the Role Manager app, and default tab is the `Home` tab, as in the image below.
</p>

{{< img-simple src="role-manager-home.png" alt="Role Manager home" class="border-0 rounded-circle" >}}

In the Role Manager app, there is a sidebar menu with the following icons.

{{< img-simple src="role-manager-menu.png" alt="Role Manager menu" class="border-0 rounded-circle" >}}

The icons meant the following (Left to Right):

1. [User Groups](#user-groups)
2. [Users](#users)
3. [Projects](#projects)
4. [Activity](#activity)

Things we can do using Role Manager App:

1. Custom user roles and groups
2. Permission management
3. App level action control
4. Monitor user logs and reports

## User Groups
<p style="text-align: justify;">
The second tab in Role Manager app is User Groups which is a collections of allowed apps and actions items.
</p>

The icon below denotes User Groups.  

{{< img-simple src="role-manager-user-groups.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this icon will open User Groups Tab.

{{< img-simple src="role-manager-user-groups-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

User Groups tab will open up, and it will show all the created User Groups.

{{< img-simple src="role-manager-user-group-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
The tab contains the user groups list with their Names, Policies and Actions. In the <b>Actions</b> column, we have the option to edit and delete user groups.
</p>

[[Read more in Editing and deleting User Groups section]]({{<ref "/apps/role-manager/editing-and-deleting-user-groups">}})

{{< img-simple src="role-manager-add-user-group-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
On the top right corner of User Groups list, there is a button to create new user Group. Clicking on <b>Create New User Group</b> button will open an Add User Group modal. With that we can add new <b>User Groups</b>. 
</p>

[[Read more in Creating User Groups section]]({{<ref "/apps/role-manager/creating-user-groups">}})

## Users

Users is the third tab in Role Manager app.

{{< img-simple src="role-manager-users.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this icon will open Users Tab.

{{< img-simple src="role-manager-users-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Users tab will open, and a list of users within the organisation will be displayed. Users tab contains two sub tabs, Users and Invites.
</p>

{{< img-simple src="role-manager-users-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
User tab contains the users list with their Names, Role, User Groups and Actions. In the <b>Actions</b> column, we have the option to edit, delete and view user groups. There is also a search bar to search for users.
</p>

{{< img-simple src="role-manager-invite-user-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
At the top right corner of <b>Users</b> list there is a button to invite user. Clicking on <b>Invite New User</b> button will open an invite user modal, which we can use to invite users. 
</p>

[[Read more in Inviting Users section]]({{<ref "/apps/role-manager/inviting-users">}})

{{< img-simple src="role-manager-invites-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
The second tab is Invites which contains the list of invited emails with their Roles, Status and Actions.
</p>

## Projects

Projects is the fourth tab in Role Manager app.

{{< img-simple src="role-manager-projects.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this icon will open Projects Tab.

{{< img-simple src="role-manager-projects-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Projects tab will open up, and it will display all projects within the organisation. It contains two sub tabs, Active and Archived.
</p>

{{< img-simple src="role-manager-active-projects.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Active tab contains a list of active projects with their Names, Managers, Members, Metadata, Locations and Actions. In the <b>Actions</b> column, we have the option to edit, delete, archive and view active projects. There is also a search bar to search for active projects.
</p>

{{< img-simple src="role-manager-add-project-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
At the top right corner of active projects list there is a button to add new project. Clicking on <b>Create New Project</b> button will open an Add Project modal, which we can use to add projects. 
</p>

[[Read more in Creating Projects section]]({{<ref "/apps/role-manager/creating-projects">}})

{{< img-simple src="role-manager-archived-projects.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
The second tab is <b>Archived Projects</b> which contains a list of <b>Archived Projects</b> along with their Names, Managers, Members, Metadata, Locations and Actions. In the <b>Actions</b> column, we have the option to edit, delete, unarchive and view active projects. There is also a search bar to search for archived projects.
</p>