---
title: "Configure a copy task between storage locations"
date: 2024-11-01T15:34:30-04:00
# layout: single
# categories:
#   - docs
# tags:
toc: true
# sidebar:
#         nav: "sidenav"
---

## Add a Copy Task

BiFrust allows you to copy files and folders from one storage location to another. The app handle the transformation of data to be copied to your destination location. All you have to do is specify which files,folders or users you want to copy from one location to another.


Click the Task Icon on side navigation on the left: <img src="/assets/images/tasksIcon.png" alt="Unblock Installer" width="30" height="30"/>


<img src="/assets/images/tasksScreen.png" alt="Unblock Installer" width="650" height="800"/>

Once in the Tasks, click on **+** button to add a new Task. 


<img src="/assets/images/tasksCopy-00.png" alt="Unblock Installer" width="650" height="800"/>

Select **Copy** as Task Type.

Select **Source** to copy data from.  
Select **Destination** to copy the data to.  
Click **Next** to specify the mapping of your copy task.

<img src="/assets/images/tasksCopy-01.png" alt="Unblock Installer" width="750" height="800"/>

Depending on the connector type you will be able to copy users, files or folder to another storage location. This can be useful to mirror and backup your data to make it redundant as an example. 

<img src="/assets/images/tasksCopy-02.png" alt="Unblock Installer" width="650" height="800"/>

This is the final configuration stage for the copy task. This is where you can set a schedule or choose data filtering options to omit or copy specific files. There is also data collision to avoid any overwriting issues.

Click **Next**

You will see the configured **Copy** Task has been added and inprogress.

Once finished, the connector will go from blue color while the Task is inprogress to red state indicating the Task has finished.

To get the detail of the Task run, click on the Task or on the ellipses and select Details.