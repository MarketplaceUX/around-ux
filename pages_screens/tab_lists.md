---
layout: screens_mobile_small
title: Prototype - Tab Bar - My Lists
category: screens
tag: tablists
protourl: http://J8LW22.axshare.com
protowindow: tablists
protosize: width=325,height=480
img: tab_lists.png
---

### My Lists
* This section allows the user to manage her Lists.

* *Click the list icon in bottom tab bar. The Close button is active here.*


### Lists
* Top section contains user's Personal Lists, as well as any Community Lists she has saved. The user's default To-Do list is always shown at the top.

* Bottom section shows a small set of nearby Community Lists - limit to 5.

* All rows show photo and name of the list creator and # of items on the list. For each each of them, profile icon links to [View Profile][1] for the list creator, and right arrow links to **View List**.

<blockquote><p>Note that user can save Community Lists in the Foursquare app, but not in the Around app. We just want to show these lists if a user has saved them through another mechanism...</p></blockquote>


### View List
* *Click 2nd row in Personal Lists section to see a Personal List. Click 1st row in Community Lists section to see a Community List. On both, back arrow is active to return you to previous screen.*

* View List is divided into 4 sections: 1) map image, 2) list creator info, 3) items not yet completed, and 4) completed items.

* The map image links to **List Map**.

* The list creator copy differs slightly for Community and Personal Lists. In both scenarios, the entire row links to [View Profile][1].

* On each Place row, user can press profile icon to go to [View Place][2] to view the Place. 

* Each Place row in the Items Not Yet Completed section contains a "Did It" button. Pressing it immediately moves the Place into the Completed Items section at the bottom of this screen. 

* If user checksin at a Place on a List, the Place item is automatically moved to the Completed Items section. Items that are auto-added are indicated (see the last item on each list).


### List Map
* Shows all the Places on the List on a larger map. Each map pin links to [View Place][2].

* *Click map image at top of list. The back arrow is active to return you to previous screen.*


### Create List
* *Click + icon on* **Lists** *screen. The Cancel button is active here.*

* *Click Create List button.* This immediately adds the new list to Lists screen. The user can see that the new list has been created (3rd item in the Personal Lists section).

<blockquote><p>Note that a new list is created with no content -- no map image and no places on the list. Content on a new list should encourage user to add Places, e.g., "Your new list needs some love. Explore some locations near you and add them to this list." And "Explore some locations" would close this panel and open the Explore Nearby tab on the Home Screen.</p></blockquote>
	
[1]: view_profile.html "Go to View Profile"
[2]: view_place.html "Go to View Place"

