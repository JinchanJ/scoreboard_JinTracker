# Game Result Tracker Overlay:
- Disclaimer:
The boxes do not work when both players have the exact same information! (This is because player info is used to detect a swap. When both players' info are the same, the program thinks a swap has occurred whenever there is an update. Hopefully, this is not an issue since players have different sponsors, Twitter handles, etc. even if they have the same name. Also identical player info should not be a problem in a tournament setting due to different seeding.)
- It is best to set the players' names before changing the score.
- Reset the score to 0-0 to have the boxes be colored from the game 1 box.
- Change Best Of to either increase or decrease the number of boxes.
- The topleft container that holds match info disappears when match info is not available. This works the same for the small phase container just below it.
- There are four types of player info chip displayed on top of the player container: seed, twitter, pronoun, and the state the player is from.

# Setup Guide:
- Download the zip file and open it.
- Move the scoreboard_JinTracker file into the /layout folder of TSH where all the other scoreboard files are located.
- Go to OBS and add a new Browser source.
- Select the /layout/scoreboard_JinTracker/index.html as the local file and set its width and height to 1920 and 1080 respectively.
- Run TSH and enter the players' information.
  
# Player Cams:
- CameraBorders.png is included to add borders to player cams.

# Customize:
- You can rename an image tournament_logo.png and put it in this file to have it be displayed at the bottom center.
- You can edit the HTML, CSS, and JavaScript files to change the color and position of words and containers, etc.

# Inspirations
- Got the idea of having boxes keeping track of who won which game from Wii Sports Resort Swordplay.
- Got the idea of putting the player info chips on top of the player container and displaying the state the player is from in one of the chips from @SevenThomsen's Sweet Spot 7 overlay.
- The overall layout having the score, player sponsor in gradient color, player name, and country flag in a container is inspired from VGBC overlays.
