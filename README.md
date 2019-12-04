# HittingChart

Gather the in game data from the user!

1. The first time we log in we should be prompted to enter our team name and our opponent's team name. 
    From then on, we should be able to select the team from a list of previously entered TEAM/SEASON options. 
    * Given that the opponent will frequently change, we will have the option to change either team name or input a new team name even after the match has been submitted through the data cleaning process.

2. Once you select your team, you can look at the ROSTER if that data has been inserted, or EDIT THE ROSTER. 
    Continue through the roster screen.

3. The VOLLEYBALL COURT MAP should appear and we should be prompted to insert Game 1 line ups. 
    Either the fields should be *directly above the court with the rotation number directly above each field** or on the court in rotational positions. Submit the line ups.

--GAMEPLAY--

4. The PLAYER NUMBERS should appear on the court in rotation position (along with all previous hitting data if the user chooses)

5. The user selects a player number and picks coordinates for the hitter and for the ball.

6. The user selects if the ball was tipped, blocked, or tooled.

7. The user select if the hit earned a kill or was dug.

8. The hit should be displayed on the volleyball court map as a straight line from the hitting coordinate to the landing coordinate with an x at the landing position for a kill on a swing and an o if the swing is dug. 
    The line should arc if its tipped. The line should touch the net and squiggle away if the attack hit the block.

-- END OF GAMEPLAY --

10. At the end of the game you should be able to enter the score of the game, and the sides should switch 
    (default to players in Game 1 starting positions, but prompt the user to make any line up changes and submit the Game 2 line up).

11. Game Play should be the same and the app should assume we are playing best 3 of 5 sets wins the match, but give the user the ability to change the settings to best 2 of 3 games wins at any time. 
    -We are just trying to get the best data possible... Also give the user the ability to end the game, or stop taking stats at any time and pick it up at a later date 
     Sometimes games are delayed for weird reasons, sometimes computers die, sometimes we are watching a replay of a game and we need to come back to our volleystat project at a later date.

12. We should have a save match data button which ideally uploads the data to a central server because that hitting data would be hella valuable.

13. Thank the users for playing volleyball and give them the option to run it back or look at the previous match data.

------------------------------------
DISPLAYING THE DATA!
Display previously logged hitting data in a groupable, sortable, filterable way.
