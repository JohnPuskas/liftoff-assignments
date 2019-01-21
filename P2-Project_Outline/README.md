# Project Outline


### Overview

Let's make music more interactive!

The goal is to engage music listeners so that they themselves are involved in the fun of creating something musical.
The idea is for users to be provided a variety of music loops within different instrument types (bass, drums, etc.) that
can be used like a musical palette. Users can select from the loops for each instrument type, 
and then play all of the instruments together simultaneously as their own new song.

If the user likes their new creation, they can save the loop selection settings of their song. Users will be able to 
listen to their saved songs at any time upon login.

I have been calling the app MeMiX ReMiX.



### Features

1) USER LOGIN: Users create accounts for logging into the app. They can then create songs, save songs, and listen to their saved creations.

2) CREATE SONG: After making selections of individual instrument music loops, users can play back their selections as one musical whole. 			

3) SAVE SONG: Users will be able to save songs that they have created. 

4) LISTEN TO SAVED SONGS: Users will be able to view and listen to songs that they have created and saved.


### Technologies

1) C#/ASP.NET Core
2) Bootstrap
3) JavaScript
4) HTML/CSS
5) Web Audio API (https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)



### What I'll Have to Learn

1) User authentication in C#/ASP.NET (I have only implemented this in Python)

2) Bootstrap

3) JavaScript - Critical for the interactive aspects of the page, and for setting up the audio player(s) properly with Web Audio API.
			  - Also, to avoid cases where the user could inadvertantly break the app.

4) Web Audio API (https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
			  - This offers a more elegant solution for the audio players, rather than relying solely on JS to patch together customized players.
			  - It provides features that potentially could be used to expand the functionality of the app beyond what is stated in this outline.			  

 It may be worth specific mention that I also want to use JS (and possibly features in the Web Audio API) to avoid having
 the web browser load ALL MP3s at one time. The webpage load time would be slow. At this time, I intend to resolve the issue by loading MP3s 
 only upon the event of user selection, and/or learning a way to manipulate buffering.


 https://www.pivotaltracker.com/n/projects/2238304