# 1514-assignment04-BetterMoquitoes

Make a fully-functioning Mosquito Attack game. This lab is out of 20 marks
 
-   (2 marks) Add states to your game. 

    -   Suggestions: Menu, Level01, Level02, Paused and Over 

    -   Make sure that the cannon and mosquito have states as well (Alive, Dying, Dead, for example) 

-   (5 marks) Make the game an actual game.  

    -   The game will have a menu screen. The game will flow through the states described above in a logical way.

    -   The player will have three lives, and move to Level02 when they dispatch of all of the mosquitoes.  

        -   When the player loses a life, the game will reduce its player count and then spawn a new player if they have any lives left. Otherwise, the game will move into the Over state. 

    -   Level02 can have the same number of mosquitoes as Level01, or be different in some way. 

-   (4 marks) Add reloading to the game.  

    -   Make the cannon be able to run out of cannonballs, and give the player the ability to reload by pressing a button.
        -   This could be accomplished by having the Projectiles stay in the Flying state even once they have left the game play area, and then setting all Projectiles to NotFlying in a method in Cannon when it's time to reload. 

    -   Add some sort of indicator to tell the player that the cannonballs have run out. The Game will have to "ask" the Cannon if it is out of cannonballs or not. 


-   (2 marks) Add a HUD to the game.  

    -   The HUD will have a separate background, and will be added to the sides, top, or bottom of the current playing screen.  

    -   The HUD should display at least these three values: 

        -   Player lives remaining 

        -   Level that the player is currently on. 

        -   Reload indicator. 

-   (4 marks) Add a different type of projectile for the cannon (with a different class, that looks differently than the cannon ball).  

    -   It should be in a separate array and be fired with a different button than the cannonball. 

-   (2 marks) Add a scale data member to all of your classes. 

-   \*Challenge\* (1 mark) Give some or all of the mosquitoes the ability to swoop down at random times.

*SUBMISSION*

Fill out the file Assignment04_Accomplishments_FirstName_LastName.md with what you accomplished in this assignment, and push your repository up before the due date.
