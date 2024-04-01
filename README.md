### startup2.0
## Elevator Pitch
There are plenty of websites that you can play tic tac toe on. I want to make one that allows for online play. The website will put you into a queue and find another player to match you with. As you play your games will be recorded and you will be able to view your record as well as a leaderboard of the top players.
## Key Features
All users will create an account with an email and a password. They will be able to play games, view their records, and check the leaderboard. The result of each game will be stored in a database and a win, loss, or tie will be added to the players' records. The leaderboard will use this information to update in real time as games are played.
## Technologies
# Authentication
Each user will have to provide an email and password to make an account and to play games. 
# Database Data
The result of the games will be added to a database that will be used to determine the record of each player.
# Websocket Data
The leaderboard will update in real time as games are played.
# Third party usage
Each page will have minimally invasive ads provided by Google's ad services to generate revenue on the page
## HTML Deliverable
For my HTML deliverable, I added the basic structure of my startup 
* HTML Pages:
3 HTML pages (index, game, leaderboard)
* Links: The login page links directly to the new game page. The new game page links back to the login page through a logout link and to the leaderboard. The leaderboard includes a logout link and a new game link
* Text: The leaderboard placeholder displays the position, name and record of players. The record placeholder has examples of a player's record.
* 3rd party service: each page has a placeholder for ads that will be provided by Google
* Images: The profile page has a placeholder image that the user will provide when creating their account
* Login: The login page has a placeholder that allows a user to inout their name and then be directed to the new game page
* Database: The information contained in a player's record and in the leaderboard will be obtained from a database.
* Websocket: The leaderboard will update in real time. 
