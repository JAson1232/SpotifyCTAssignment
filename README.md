
Spotif Classification Assignment 

The contents in this repo are the spotify csv file which contains all the songs and their data and a spotiff.ipynb file which is the jupyter notebook in which the tasks are
adressed. Here is the description of the tasks:


Assume you want to create a program that mimics Spotify’s “Discover Weekly.” Your program will of course be much simpler due to time and resource constraints. Discover Weekly generates suggestions for users of Spotify: a few new songs every few days, possibly songs that the users have not heard but will most probably enjoy.

We will assume the following in this problem: 

You have 100 users, who use your main app, which resembles Spotify. You are launching a new feature for an app imitating “Discover weekly”. This new feature will also suggest to the users what songs they can listen to, that they may like. This means that you will be looking at what songs people played in the app and we will suggest new songs to them, in the new feature, based on what we know. The suggested 5 songs may be songs the user has played. 

Week 1 after the day of the launch - Individual choice
Each of your 100 users is trying the new Discover feature in your app for the first time, in the first week. The feature will generate songs that he or she may like. You need to generate 5 songs. Assume this is the first week in which you launched your app on the google store. 
 
Assume that all users start using the feature on day 1 and no one downloads it later. The 5 songs that will be generated for the first time we pick in the following way:  
 
You already have 100 pre-made playlists, with 50 songs in each. Your task is the following: if you find a playlist that contains 3 songs that the user has listened to already and 3 he has not heard yet, you select this playlist. From this playlist, your algorithm picks any 5 songs. 

Week 2 - Genres
In the second week you will use a different approach: 
A user opens the app and is looking for new suggestions on “Discover.”  
 
There are three types of music only: pop, rock, and techno.  
 
You want to find which style the user has listened to the most, of those three. Define in your own terms what this should mean. For example, you can say that if the user has listened to 20 rock songs and 2 techno songs, and 3 pop songs, this is a rock music fan. Or you can work with percentages: you can find a user that played 80% techno and 20% pop. You can make your algorithm disregard a difference of 10% and say that if a user played pop 45 percent of the time and rock 50 percent of the time, the difference is small and both styles should be considered equally important to him or her. Outline your scale and assumptions in your work. 

In the second week, your algorithm should suggest 5 songs again, this time based on the above-mentioned, i.e. based on style. 
 
It is possible that the program suggests one song in one week and again the same song in the following week.

Week 3 - Shifts
In the third week after the launch, you want to account for a user’s mood shift. We have a few types of songs: “happy”, “party”, “calming”, and “lounge.” Define in your own algorithm if you think one song can be classified as two of those at the same time.  
 
This week you need to select 5 more songs to suggest to each user, again. If last week the user was playing a lot of songs from one of those types, this week we want to suggest more of the same type. Define, in your own terms what this should mean: if the user listened to 3 “calming” songs, should we provide 3 more without considering other factors? What if he or she also listened to 3 “party” songs and 4 “lounge” style songs?
A brief description of the project, including its purpose and any relevant background information.




Getting Started

The notebook provides the installation for the requiered libraries. In the case that these installations do not work please install the sklearn library alongside the padas and numpy libraries


Usage

Please run the cells one after the other in order as running them in a different order may result in errors. In the case of an error start the notebook from scratch and run the cells in order


License
All content in this repository is submitted to VU Amsterdam as an assignment for a class project. All rights go to the members of the group that developed these algorithms and VU


Additional Resources
For any questions or extra information please do not hesitate to contact any of the group members, we are happy to help :) 

Happy grading <3
