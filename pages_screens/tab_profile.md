---
layout: screens_mobile_small
title: Prototype - Tab Bar - My Profile
category: screens
tag: tabprofile
protourl: http://BTSFJQ.axshare.com
protowindow: tabprofile
protosize: width=330,height=480
img: tab_profile.png
---

### My Profile
* This is how the app user manages her Profile. 

* *Click the user icon in bottom tab bar. Then click the tabs to view their content. The Close button is active here.*

* NOTE: Throughout the rest of the application, a user may see content rows about herself. E.g., the user has liked a Place; on the Likes screen, she would see a content row about herself. When the user presses her own content row anywhere in the app, the My Profile panel will open, rather than linking to View Profile.


### History Tab
* Shows a list of user activity. 

* Each row contains photo of user and copy about the activity. Each row links to View Place or View Profile.

* First 4 rows link to [View Place][1] because they are about the Place rather than a Person.

* 5th row links to [View Profile][2] because it is about a Person.

* 6th row is not linkable (complete Badge content is not part of this sample app).


### Friends Tab
* All rows link to [View Profile][2] for the relevant friend.


### Add Friends
* *Click Add button on the Friends tab.  The back arrow is active to return you to previous screen.*

* *<em>See [question][3] about adding friends</em>*.


### Requests Tab
* Friend requests are shown in this tab. The number on the Profile icon in the bottom tab bar indicates how many Friend Requests are pending in this tab.

* In each row, profile photo links to that person's [View Profile][2].

* Accepting the request immediately removes the request from this tab and adds the friend to the Friends tab.

* Ignoring the friend request immediately removes the request from this tab.

[1]: view_place.html "Go to View Place"
[2]: view_profile.html "Go to View Profile"
[3]: ../pages_issues/index.html "Go to question"

