# Project Outline


### Overview

Let's make music more interactive!

The goal is to engage music listeners so that they themselves are involved in the fun of creating something musical.
The idea is for users to be provided a variety of music loops within different instrument types (bass, drums, etc.) that
can be used like a musical palette. Users can select from the loops for each instrument type, 
and then play all of the instruments together simultaneously as their own new song.

If the user likes their new creation, they can save the loop selection settings of their song. Users will be able to view
each others saved songs, and upvote their 3 favorites.

I have been calling the app MeMiX ReMiX.



### Features

1) USER LOGIN: Users create accounts for logging into the app. They can then create songs, save songs, and vote on other users' songs.

2) CREATE SONG: After making selections of music loops, users can play back their selections as one musical whole. 
			Several audio players will be synced together for this functionality to work.

3) SAVE SONG: Users will be able to save songs that they have created. 
			The idea is for each music loop MP3 to be represented by an integer in the back end, and to use the corresponding integers to 
			later render the proper MP3s together as a song by using switch statements in an ASP.NET Razor page.

4) USER VOTING: Users will be able to upvote the songs of other users. There will be a specific web page to display the top vote-getters.

5) SONGS VIEWING: This may go without saying, but users will be able to not only view and listen to their own saved songs, but the saved songs of other users.
			At the absolute very least, users should be able to view ALL songs (which will require pagination). Sort, filter, and search features are possibilities.



### Technologies

1) C#/ASP.NET Core
2) Bootstrap
3) JavaScript
4) HTML/CSS
5) Web Audio API (https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)



### What I'll Have to Learn

1) User authentication in C#/ASP.NET (I have only implemented this in Python)

2) Bootstrap

3) JavaScript - Critical for the interactive aspects of the page, and for setting up the audio player(s) properly with Web Audio API
			  - Also, to avoid cases where the user could inadvertantly break the app.

4) Web Audio API (https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
			  - This offers a more elegant solution for the audio players, rather than relying solely on JS to patch together customized players
			  - It provides features that potentially could be used to expand the functionality of the app beyond what is stated in this outline			  

 It may be worth specific mention that I also want to use JS (and possibly features in the Web Audio API) to avoid having
 the web browser load ALL MP3s at one time. The webpage load time would be slow. At this time, I intend to resolve the issue by loading MP3s 
 only upon the event of user selection, and/or learning a way to manipulate buffering.


 https://www.pivotaltracker.com/n/projects/2238304