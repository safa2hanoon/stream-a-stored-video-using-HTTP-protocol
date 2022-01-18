# stream-a-stored-video-using-HTTP-protocol
Multimedia Project --> 
Course Project #1– Multimedia Networking
Department of Electrical and Computer Engineering
First Semester 2021/2022
Course Project
In this project you will stream a stored video using HTTP protocol. To complete the project do the following:
  1. Download three videos from the internet or use any other sources to get the videos. The videos should be of different resolutions.
  2. Setup a webserver server on a server using docker containers. You will be given an account on a server dedicated for this project. You should refrain to use it for any other purpose.
  3. Create a Hello webpage (blank webpage with Hello text) on the server,
  4. Use port forwarding on the server (docker container) and in the ssh command to test the server and view the Hello webpage locally (at localhost or 127.0.0.1),
  5. For each video in point 1, follow the guidelines for Smart encoding of uploaded videos for adaptive bitrate streaming of Microsoft (https://docs.microsoft.com/en-us/stream/network-overview) to do
the following:
    a. Use ffmpeg to process the downloaded video to generate videos with different qualities,
    b. Use ffmpeg to process the downloaded video to generate videos with different resolutions,
  6. Use the MP4Box software tool to produce DASH compatible video stream; manifest (.mpd) and video files (.m4s) and store these files in the root directory of the webserver,
  7. Create a main webpage that have links for three video stream webpages. In each of the video stream webpages add the JavaScript player as shown in the lecture slides.
  8. Use any internet browser to view the three webpages locally and play the video.
  9. To validate how your web pages load and stream video in poor network connections
    a. Perform network throttling in your browser to simulate poor network and view in the downloaded video chunks
    b. Use any webpage testing platform such as BrowserStak to simulate network conditions on mobile devices.

use this link to open my website : 
http://176.119.254.185:8029/

