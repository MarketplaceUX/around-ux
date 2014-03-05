---
layout: screens_mobile_small
title: Prototype - My Profile
category: screens
tag: tabprofile
protourl: http://BTSFJQ.axshare.com
protowindow: tabprofile
protosize: width=330,height=480
img: tab_profile.png
---

### My Profile
* <span class="proto-color">Click the user icon in bottom tab bar. Click tabs to view content. Click close at any time to close panel.</span>
* This is how the app user manages her Profile. 
* If user clicks a Profile row that is about himself within the rest of the application, that action should open this Profile panel (rather than linking to View Profile).


### History Tab
* Shows a list of user activity. Each row has photo of app user and copy about the activity.
* Rows link to View Place or View Profile.
* First 4 rows link to View Place because they are about the Place rather than a Person.
* 5th row links to View Profile because it is about a Person.
* 6th row is not linkable (complete Badge content is not part of this sample app).


### Friends Tab
* All rows link to View Profile for the relevant friend.


### Add Friends
* <span class="proto-color">Click Add button on Friends tab.  Click back arrow to return to previous screen.</span>
* Let's do whatever is easiest here. Maybe just one service? Or just phone contacts?


### Requests Tab
* Friend requests are shown in this tab. The number on the Profile icon in the bottom tab bar indicates how many Friend Requests are pending in this tab.
* In each row, profile photo links to that person's View Profile.
* Accepting the request immediately removes the request from this tab and adds the friend to the Friends tab.
* Ignoring the friend request immediately removes the request from this tab.