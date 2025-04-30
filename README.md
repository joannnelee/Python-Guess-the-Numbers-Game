# Python Guess the Numbers Game

In this project a guess the numbers game will be created on python. 

### Prerequisites 

Python should be used to run this game

#### The following libraries should be installed:
- 

### How the game works 
A guess the number game is created where a player has 3 attempts to correctly guess a randomly generated number from 0-10. If the player guesses incorrectly a prompt will appear which informs them if they were ‘too high’ or ‘too low’ and then allows them to guess again. If all attempts have been used, then the player loses the game and a message will appear notifying the player that they used up all their attempts. If the player wins the game they will receive a message notifying them that they guessed correctly and they will earn 1 point towards their overall score. At the end of each game, a prompt will appear asking if the player would like to play the game again.

### Flowchart

<img width="745" alt="Screenshot 2025-04-30 at 11 44 32" src="https://github.com/user-attachments/assets/e4fe4b8c-ae50-4d38-b5dd-8ac885a34bc3" />

1. The game starts with the computer randomly generating a number from 0-10.
   
2. The variable attempts is set to 0 - this variable counts how many attempts the player has made to guess the number.
   
3. Attempts = max_attempts - attempts. The player is notified how many guesses they have remaining. 
   
4. The player is prompted to guess a number from 0-10.

5. If the player guesses correctly a message appears saying "You guessed correctly" and the player earns 1 point. Go to step 9, otherwise go to step 6.

6. If the player guesses incorrectly +1 is added to attempts.
 
7. If attempts == max_attempts then the player loses the game. Go to step 9.

8. If attempts < max_attempts, the player is notified their guess is 'too high' or 'too low'. Loop back to step 3.

9. The player is notified of their score and asked if they would like to play again.

10. If the player selects 'no' the game ends. If 'yes' then loop back to step 1.





