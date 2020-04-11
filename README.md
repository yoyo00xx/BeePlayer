# BeePlayer #

BeePlayer is an application level media player for Android. It provides an
a collaborative alternative to Android’s MediaPlayer API for playing audio and video both
locally and over the Internet. BeePlayer supports features not currently
supported by Android’s MediaPlayer API, including DASH and Collaborative Video Streaming using Wi-Fi Direct


## Using BeePlayer ##

BeePlayer may be installed as an APK on Android Version 10 or later.

## Development Milestones ##

1. Developing the UI Functionality with base ExoPlayer (Exoskeleton)
2. Modify ExoPlayer to accomodate Collaborative Streaming
  a. Introduce a Common Storage where Wi-Fi Direct stores incoming video segments 
  b. Integrate Segment Assignment into the ExoPlayer Downloader 
  c. Serve Optimal Bit rate per segment through HTTP requests
3. Record a live demo on 2 devices



#### Credits ####

Developed by Asaad AlGhamdi & Younes Balah. Supervised by Dr. Muhamad Felemban
