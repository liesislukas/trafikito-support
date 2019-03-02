---
featured_image: trafikito-what-is-a-workspace.png
id: 2604162f-3a0f-482d-b6c2-6cdc7f8d2b69
layout: blog
sort: 1
title:  "What is a workspace?"
uri: what-is-a-workspace
tags: [workspace]
---

At Trafikito you can monitor several servers at once. Whether you have a database running on 3 servers, a web application on another, some caching on the next or maybe several projects and microservices running on different machines. The bottom line is <strong>you need to monitor several different machines at once</strong>. With Trafikito you can combine all servers in a single workspace and have a great overview of all your servers at once.

<!--more-->

A Workspace is like a container for several monitors. A single workspace contains:

1.  Servers to monitor
2.  Members

![Workspaces at Trafikito (servers list)](../assets/img/blog/trafikito-workspace-servers-list.jpg)

Servers Management
------------------

The Initial view of any workspace is your list of servers. In this list, you can see how all of your servers are doing. On the left, you can see the overall status and It may be:


<div class="t-flex-align-center t-m6">
    <div>1.</div>
    <div class="t-range-normal t-mh6"></div>
    <div>Everything's <strong class="t-mh3">ok</strong></div>
</div>
<div class="t-flex-align-center t-m6">
    <div>2.</div>
    <div class="t-range-warning t-mh6"></div>
    <div>At least one monitored value is in the <strong class="t-mh3">warning</strong> range</div>
</div>
<div class="t-flex-align-center t-m6">
    <div>3.</div>
    <div class="t-range-error t-mh6"></div>
    <div>At least one monitored value is in an <strong class="t-mh3">error</strong> range</div>
</div>

![Workspaces at Trafikito (servers list)](../assets/img/blog/trafikito-workspace-servers-list-something-wrong.jpg)

This list **refreshes automatically** per minute to ensure the overview is current.

Also, you have the option of adding more servers, viewing Trafikito installation instructions and removing a server. This is all done in the same clean list of servers in the selected workspace.


Members Management
------------------

The Free plan allows only one member in a workspace but with the paid plans you can add up to **30 members**. Also, you can be a member of several workspaces at once. After registering, you automatically get the default workspace but you can delete or make changes if you desire.

The User that creates a workspace automatically becomes the owner of it and any new user will have the role of a member.

![Workspaces at Trafikito (members list)](../assets/img/blog/trafikito-workspace-members-list.jpg)