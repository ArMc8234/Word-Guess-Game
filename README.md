# Word-Guess-Game

# Overview:  The word guess game is a simple introduction into javascript.  It employees Bootstrap to define the spacing for the header and game containers as well as a small style sheet for the background.

# The logic required an alphabet array and solutions array to contain the puzzle solutions and all of the possible guesses.  A regular expression was used to identify all of the letters within the solution and replace them as blanks when the game begins and resets.

# A function was created to listen for the user guess, then run a condition that compared the user guess to all of the letters in the solutions array. If the user guess is found in the solutions array, then it replaces the blanks with the chosen letter where they appear within the solution. If the user guess is incorrect, then the incorrect guess is pushed to a wrong guesses array, then the documentById method returns the updated incorrect guesses array to the appropriate div for display in the browser.

# There is also a counter that tracks the number of wrong guesses and concludes the game when the total number of wrong guesses reach seven.

# This project was a special one for me because it was my first time creating a page that had action! Javascript was brand new to me at the time and it was a fun and nerve-racking all at the same time.  I also got to put some personality into the creation by creating a theme around a well-known figure. 

# I hope you check out the finished product and have as much fun playing it as I had in creating it!