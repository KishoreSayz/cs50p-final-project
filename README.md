CS50P-Final-Project
Description
This is a final project for cs50p course .
In this game you shoud guess the 5 letter word in 6 tries . The word is a singular noun,where letters can be represented 
After evry attempt he user sees colored guess distribution.
* If the letter is in the word and in the right spot , it turns green
* If the letter is in the word but in the wrong spot, it turns yellow
* If the letter is not in the word, it turns white

  In this program I tried to prevent potential mistakes and added some features.
  1. A target word is picked randomly from the .txt file with 5-letter nouns.
  2. The user's guess word is checked to be a 5-letter word
  3. The user's guess word is checked to be singular noun in FREE DICTIONARY API
  4. Identical letters in words are controlled .
  5. After printing the user's name a stopwatch starts and goes till the victory or last try.
  6. When the game is over, the user can copy guess distribution made with emoji.
  7. It is necessary to install the modules
  8. Then run is command - python project.py

  Main files
  * project.py- main file with the game
  * test_project.py- three tests of the main program's functions
  * five-letter-words.txt- the list with 5-letter nouns.

  Acknowledgement
  I would like to express my deepest appreciation to David Malan and the whole CS50 team for entertaining lectures and helpful problem sets.
