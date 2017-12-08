---
title: vBulletin API and Mobile Application Options
slug: vbulletin_api_and_mobile_application_options
taxonomy:
    category:
        - settings
    tag:
        - options
        - api
visible: false
template: article
version: 5.3.3
date: 12/06/2017 11:16pm
---

## Enable vBulletin API
Allow clients to connect to the vBulletin API. <br /><br />Please remember to generate an API key <a href="admincp/api.php">here</a> to allow the API to work.


Enables the API log, allowing administrators to track client behavior (or for debuging purposes). Only enable this option if you really need it. The log is stored in the database and can rapidly become large in size.


When "Enable API Log" is set to "Yes", this option decides whether to log API POST parameters. Please note that POST parameters can contain a lot of data, which can in turn can take up large amounts of database space.


This is the maximum number of items to display in TOP/NEW section on the Home page of mobile application. This limitation applies to every content type including 'All Content', 'Forums', 'Blogs' and 'Articles'.


Set the cutoff (in days) for the display of Topics in the Home page TOP/NEW section of the mobile application. Only Topics created after the cutoff will be displayed. If you have a big board, setting this to a lower number may improve performance.


You can choose to display topics in specific forums in TOP/NEW section on the Home page of mobile application. Separate forum IDs with a comma.<br />Example setting: 10,25,30


Set the cutoff (in days) for the display of Blog Entries in the Home page TOP/NEW section of the mobile application. Only Blog Entries published after the cutoff will be displayed. If you have a big board, setting this to a lower number may improve performance.


You can choose to display blog entries in specific categories in TOP/NEW section on the Home page of mobile application. Separate Categories IDs with a comma. -1 means Uncategorized entries.<br />Example setting: 10,25,30


You can choose to display blog entries post by specific users in TOP/NEW section on the Home page of mobile application. Separate User IDs with a comma.<br />Example setting: 10,25,30


Set the cutoff (in days) for the display of CMS Articles in the Home page TOP/NEW section of the mobile application. Only Articles published after the cutoff will be displayed. If you have a big board, setting this to a lower number may improve performance.


You can choose to display CMS articles in specific categories in TOP/NEW section on the Home page of mobile application. Separate Categories IDs with a comma.<br />Example setting: 10,25,30


You can choose to display CMS articles in specific sections in TOP/NEW section on the Home page of mobile application. Separate Section IDs with a comma.<br />Example setting: 10,25,30


Enabling this option will allow mobile api users to register their devices with the forum and receive push notifications via Firebase Cloud Messaging.
In addition to this option, the server must have a valid "Firebase Cloud Messaging Server Key" below for push notifications to function.


This is the "Server key" found in the "Cloud Messaging" Tab of your Firebase Cloud Messaging project. <br />
You can get to this tab via (as of 2017-05-18)
https://console.firebase.google.com/project/{projectid}/settings/cloudmessaging/
Where {projectid} is the unique id assigned to your firebase project. <br />
<br />
After you save this option, you can test the server key <a href="admincp/fcm.php">here</a>.


