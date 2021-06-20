# Rock-Paper-Scissor-game

First, we import randint  from the random module. This is how our computer opponent will play.
There are three possible plays you and the computer can make on each turn, “Rock”, “Paper” and “Scissors”.
Once the while loop starts, the computer will patiently wait for you to make a play. As soon as you take your turn, your status changes from False to True because any value assigned to the variable player makes player True. We use the input() function to pass the new value to the variable player. Your input will determine which statement is triggered.
Using nested if/elif/else statements, we check every possible outcome of the game and return a message stating the winner, a tie, or an error.
We use else at the end to catch anything that isn’t “Rock”, “Paper” or “Scissors”. Finally we reset the player value to False to restart the while loop.
