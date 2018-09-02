# Create a video chat app
---------------------------

We are working on a self driving car solution. 

We need a way to stream video from car to control room. To do this we need an application that allows us to stream the video.

We have identified a partial goal to create a video chat app within next 10 weeks. And to make it interesting we are planning to launch the app and actually try to sell it (for free) to users - with a tagline: Instagram for video chat. Since we are machine learning experts- we are thinking about adding some cool video effects - that goes way beyond what FB is currently offering. Spend about 4 weeks  with this activity that will not be useful for the final product - but we may able to fork to a new path with this app standalone.

## Week 1 - 10% toward the goal
We will be using webrtc to create the video chat application. This weeks goal is to make the webrtc sample apps work on LAN environment.

Success criteria:
- Be able to configure webrtc build using chromium project.
- Be able to do video chat between two machines running either linux or android 
- Post youtube video that shows the video is being streamed properly.

### Result at the end of week 1:
Build the webrtc subpackage of chromium package and now are able to run the sample client and server and those can connect successfully. Have taken the video and posted on youtube unlisted video https://www.youtube.com/watch?v=fJsgKMfRkpQ .

### Problems faced:
The webrtc can not be built with python 3.6 and then when tried to use anaconda with python 2.7 the build system complained about unknown python. Had to remove anaconda and restore Ubuntu default python 2.7 to build webrtc.

### Work not finished in time:

Tested the build from one system without connecting two different client on separate machine. To fix this we need to setup another test machine with ubuntu and a webcam. Estimated time required 2-6 hours.

---------------------------------

## Week 2 - 20%
Create signaling server on AWS account

### Success criteria:
    The clients are able to communicate using the signaling server that is deployed in AWS account.

## Week 8
### Add the 

## Week 5 - 50%
Recruit users

### Success criteria:
    Have at least 5 users who are using the app.


## Week 10 - 100%
Launch version 1 of the app in google play or app store.

## Week 11
Decide if the application itself is a promising product to create a company around it.

### Success criteria:
    A clear decision to go forward or not.

## Week 15
Get 100 active users.

### Success criteria:
    Users must be using the app 2 times a week to call a friend to be considered active users.
