---
layout: post
title:  "How to change the name of a current command?"
uri: how-to-change-the-name-of-a-current-command
tags: [data sources]
---
To change the command name you need to login to your server and update `/opt/trafikito/available_commands.sh` file.

<!--more-->


1.  Login to your machine. You can use SSH, FTP or anything else depending on your machine.
2.  Edit this file: `/opt/trafikito/available_commands.sh`
    1.  If this file is not available, Trafikito agent is not installed yet or it is installed at a custom location
3.  Edit the alias of the command at the end of the file.
4.  Save the file and wait a couple minutes.

#### Warning:

If any data sources were using the changed command, you must update those data sources to use the new command. 
If the new command is not available yet on the dashboard, make sure to wait a couple minutes for the new data to come.