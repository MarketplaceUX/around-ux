---
layout: screens_mobile_small
title: Prototype - Tab Bar - Checkin
category: screens
tag: tabcheckin
protourl: http://SE2YPW.axshare.com
protowindow: tabcheckin
protosize: width=325,height=480
img: tab_checkin.png
---

###Checkin
* <span class="proto-color">Click map pin icon in bottom tab bar. Click close at any time to close panel.</span>
* This is the primary method by which the app user checksin to Places (secondary method is checking in via View Place).


### Choose Location
* <span class="proto-color">Start flow by clicking map icon in bottom tab bar</span>
* Shows rows for Places around the user's current location. Each row links to Add Comment.
* User can also search for a Place. This would open keyboard to enter address or name. After entering text, user is returned to this tab/screen showing showing results. Should work like Search does from Explore Nearby tab on Home Screen. 
* Does this address the slow geo-location, or do we need something more substantial for this sample app?


### Add Comment
* <span class="proto-color">Click top Place row on Choose Location. Click back arrow to return to previous screen.</span>
* User can check-in without adding a comment. <span class="proto-color">Click Check-in button without clicking into input field to see this.</span>
* Or user can add a comment to the checkin. <span class="proto-color">Click input field to see keyboard; then click Check-in button to see this.</span>


### Completed
* <span class="proto-color">Click Check-in button on Add Comment</span>
* Shows Points and Badge (if any) earned for this checkin.