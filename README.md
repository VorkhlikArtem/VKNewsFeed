# VK News Feed
VKontakte news feed application where various JSON APIs are used directly from the VKontakte server.  
A user can scroll his news feed, expand text in posts, scroll photos with the beautiful custom horizontal layout, refresh the feed to get new posts.

## Technologies 
- Clean Swift Architecture
- VK SDK 1.3.8 (User Authorization/Registration, VK SDK API)
- Carthage
- Asynchronous Loading and Caching Images

About layout:
- Manual layout with Frames in UITableViewCells
- Auto Layout Programmatically (NSLayoutAnchor and Anchor Extension)
- UITableViewCells dynamic resizing
- Nested UICollectionViews Custom Layout

## Overview 
User's avatar in VK is getting fetched while authorization and is placed on the navigation bar.  
A user can tap on "Show all" and expand full text in a post.  
Every time, a user scrolls to the 4/5 of the table view's content size, previous (older) posts are starting to be fetched and then they will be added to the end.

</p>
<p align="center">
<img src= "https://github.com/VorkhlikArtem/VKNewsFeed/assets/115653999/fb562acd-ecda-498e-9943-d2cd25008cba" width="250">
<img src= "https://github.com/VorkhlikArtem/VKNewsFeed/assets/115653999/6978f26e-0646-4d5e-8b6d-1ca37d86aca6" width="250">
<img src= "https://github.com/VorkhlikArtem/VKNewsFeed/assets/115653999/264b6b26-6a09-4d6e-bd5d-284ec6b4ee59" width="250">
</p>

</p>
<p align="center">
<img src= "https://github.com/VorkhlikArtem/VKNewsFeed/assets/115653999/d33e1d73-9737-46b3-ae50-d3031dc2ae22" width="300">
</p>

## Requirements
- IPhone 7+
- iOS 13.0+
- XCode 13.0+

