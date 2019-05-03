# Game-of-Nim
Write a Java program to simulate the game of Nim between two players. Either or both of the players may be a Human, a SmartComputer, or a BelowAverageComputer. 

	Begin each game by asking the user who will be playing and which player should go first.

-- The BelowAverageComputer removes a random number of marbles between 1 and n/2 each turn.  (n is number of marbles remaining)

-- The SmartComputer removes exactly enough marbles to make the remaining pile size a power of two minus one (i.e. 1, 3, 7, 15, 31, or 63).
	The SmartComputer cannot be beaten if it has the first move, unless the initial pile size happens to be 15, 31, or 63.  Naturally, a Human who plays first and knows the winning strategy is also invincible.

-- The Human enters the number of marbles to be removed interactively  
	
	Begin each game with a pile of between 10 and 100 marbles, inclusive, where the size is set randomly.
 
	After each turn, print out the player name, number of marbles taken, and the number of marbles remaining.

	When each game ends the winner should be announced and the user asked whether she wants to play another game.  If so, the user will enter the players and play order again.
