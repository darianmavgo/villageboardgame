# Village Board Game "Kenya" 
In 2009 and some of 2010, I built a board game. Unfortunately the core javascript of the game is missing still.  In the kenya.html file you will find all of the templates for every dialog in the game.  I'm also adding the google sheets that contains all the settings for each spot on the village board. 
The original board matched the 40 spaces of the original Monopoly design.  I downsized the board to 20 spaces to better fit on the screen at the time.  
# Found
* Deeds table google sheet.  I've committed it as csv. This details the all properties of each space on the Village board.  
* Cards table google sheet.  I've committed it as csv.  This details all the cards that can happen during gameplay.  
* Village globals google sheet. I've committed it as csv. I created a sheet that javascript feeds into a globals object and uses throughout gampeplay.  
* Courtesy of Internet Archive I found the slightly butchered original prototype html, committed to this project as kenya.html. 

# Still Missing 
* main style sheet
* main javascript file that used all the data sheets and updated the html.  
* the fish, the bear, and bofa symbol I used as the original 3 players is gone probably. 

# Functionality
* Only single player or multiplayer with people taking turns on the same computer.  
* No server-side persistence.  Reloading the page completely resets the game.  All progress gets lost.  
* No secrets for a given player.  Since it's share the computer style there's no secrets between players.
* Control panel on the side that allowed for lots of cheats for quick testing of any new game rule.
