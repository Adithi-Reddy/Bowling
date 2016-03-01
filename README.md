# Bowling
Write a node module which implements a game of bowling (see http://bowling.about.com/od/rulesofthegame/a/bowlingscoring.htm for a description of how bowling is scored).  The application should expose to REST service to calculate a bowling game score:
•	AddUser - To add a user (id and name) . Method to add use Id and name.
•	DeleteUser - To delete user (id)
•	Play- Pass userid and  a string between 12 and 21 characters long where each character represents a throw: X for a strike, / for a spare, or a number indicating how many pins were knocked down.
•	RealTimePlay - The Game class should define a function that takes a single argument indicating the score of one throw and userId, and returns the running score for the whole game.
•	Score - Takes userId and should return the current total score and username.
Notes:
•	Structure your project well 
•	Unit test the logic
•	Keep in mind scalability and multiple user access
•	Clarity is valued over cleverness.
Example games:
•	Game('XXXXXXXXXXXX').score == 300 , player - TOM
•	Game('90909090909090909090').score == 90 , player - JERRY
•	Game('5/5/5/5/5/5/5/5/5/5/5').score == 150 , player - TOM
•	Game('X7/729/XXX236/7/3').score == 168 , player - ANDREW
•	Game('00000000000000000000').score == 0 , player - TOM
•	Game('01273/X5/7/345400X70').score == 113 , player - TOM
•	Game('X7/90X088/06XXX81').score == 167 , player - MIKE

