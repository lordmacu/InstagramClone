# InstagramClone
An Android clone of the Instagram app.
# Codepath Task List App

Time spent: about 30 hours spent in total 

Completed user stories:

 * [x] Required: User can scroll through current popular photos from Instagram.
 * [x] Required: For each photo displayed, user can see the following details: Graphic, Caption, Username 
 * [x] Optional: Relative timestamp, like count, user profile image.
 * [x] Optional: Add pull-to-refresh for popular stream with SwipeRefreshLayout
 * [x] Optional: Display each user profile image using a RoundedImageView 
 * [x] Optional: Improve the user interface through styling and coloring
 * [x] Optional: Allow video posts to be played
 * [x] Anything else that you can get done to improve the app functionality or user experience! - can play/pause the video in the feed itself. Also added the username next to the profile piture as in the Instgram app.


Challenges:

I created a different layouts for list items that displayed a photo vs a video. 
What is correct approach when you want to display types of views in a list? 
The ViewHolder pattern also becomes slightly less effective with this approach because you may have attached a view of the incorrect type to the recycled list item. For example, you may have to convert a recycled list item that was displaying a photo to display a video.

Notes:

Code improvements I'm awar eof that I didn't have time for include:
* Creating a seperate model for InstagramVideo 
* Implement View Holder pattern
* move networking/deserialization code out of the activity, it doesn't belong there
* Handle exceptions thrown when deserializing the result from the photos endpoint.

Walkthrough of all user stories:

![Video Walkthrough](https://github.com/nidhik/InstagramClone/blob/master/codepath-assignment-week1-android.gif)
GIF created with [LiceCap](http://www.cockos.com/licecap/).
