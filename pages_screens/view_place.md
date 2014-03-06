---
layout: screens_mobile_small
title: Prototype - View Place
category: screens
tag: place
protourl: http://HTVFJF.axshare.com
protowindow: place
protosize: width=320,height=480
img: view_place.png
---

### View Place
* <b>Note:</b> Some interactions change the screen content. You may need to reload the prototype to start "fresh" if you've made some changes.

* View Place is accessible from a few places in the app. Once on View Place, user presses back arrow to return to previous screen.

* Via the top header user can access the **Share panel**.

* Below the header is a map plotting the Place location. The map links to **View Place Map**.

* Below the map is a row devoted to the current Place Mayor. This entire row links to the mayor's [View Profile][1].

* Primary actions on this screen are **Checkin** and **Like**.

* Beneath the primary actions, the likes row contains the current number of likes for this Place. The row links to **View Place Likes**.

* Below the likes row are the most recent 3 Tips for this Place, as well as **Leave a Tip** button. **See All Tips** button is here only if there are more than 3 Tips.

* Below the Tips section is a list of 3 Community Lists on which this Place appears. Each List row links to **View List**. User can **save the Place** to one of her Lists. To keep it simple, choose the most recent created/updated Lists on which this Place appears.

* At the bottom of the screen are photos of the Place. Each links to **View Place Photo**. Users can also upload a photo.

* Because Foursquare has a lot more info, also included is a link to view this Place on the Foursquare site.


### Share Place
* User can share the Place by SMS or Email via Firefox OS.

* *<em>See [question][3] about sharing</em>*.


### View Place Map
* *Click map image to see View Place Map. The back arrow is active to return you to the previous screen.*

* Map pin doesn't link anywhere, because we're already on the View Place screen.


### Checkin to this Place
* *Click the Checkin button to checkin to this Place. The Cancel button is active here.*
* Once the panel is open, *click Checkin button.*

* After checking in, user sees Checkin Completed screen (repurposed from the Checkin tool flow). This contains point stats for the checkin, as well as any Badges earned for the Checkin. *Click the back arrow to return to previous screen.*

* Note that the Checkin button has been changed to indicate you've checked in to this Place.


### View Place Likes
* *Click the likes row to see View Place Likes. The back arrow is active to return you to the previous screen.*

* View Place Likes is a list of people who've liked this Place. Each row contains profile icon and username. Each row links to [View Profile][1].


### Like this place
* *Click the Like button.* Liking the Place immediately increments the number of likes on View Place.

* It also updates View Place Likes by adding your like to the top of the list. *Click the likes row again to see the new like added to the list.*

* User can un-like the Place by pressing the Like button again. *Un-like the Place and then click the likes row to see that the like was removed from the list.*


### View Tips
* *Click See All Tips button to see View Place Tips. The back arrow is active to return you to the previous screen.*

* Row format for See All Tips is the same as for [See All Comments][2] on View Checkin -- here, the tip text is the most important content. Each tip row links to [View Profile][1].


### Leave a Tip
* *Click Leave a Tip button to add a tip. The Cancel button is active here.*

* When the panel is open, *click Leave Tip button to add a tip to the Place.*

* After leaving a tip, user sees confirmation that the tip was posted. 

* *<em>See [question][3] about task confirmation</em>*.

* After closing the confirmation, user can see that the Tips sections now show the new tip. *Click See All Tips again to see that the new tip was added at the top of the list.*


### View List
* *Click the 1st Community List row. The back arrow is active to return you to the previous screen.*

* View List in this context has same content and interaction as the list views in the My Lists tool.


### Save Place to List
* Save Place to List shows all of the user's lists, both Personal and Community. User can save to existing List or create a new List to save to.

* *Click Save Place to List. Then add to list, or create a new list and add to it. The back arrows and Cancel button are active to return you to the previous screens.*

* After saving the Place to a List, user can see that the Place was saved to her List.


### View Place Photo
* Pressing any photo opens the photo in a larger view. The larger view contains a header like other pages, including a back arrow that returns user to View Place.

* The larger view includes forward/backward arrows beneath (or on top of) the photo so user can page through all the Photos attached to this Place. Also include X of Y indicator for each photo.


### Upload Photo
* User can upload a photo. 

* *<em>See [question][3] about uploading photos.</em>*


[1]: view_profile.html "Go to View Profile"
[2]: view_checkin.html "Go to View Checkin"
[3]: ../pages_issues/index.html "Go to question"


