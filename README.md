# Higher-or-Lower-game
This is an interactive command-line guessing game where the user compares two public figures, brands or organizations and predict which one has the larger social media following. Each crrect guess increases the users score and brings a new challenger into the game.

# The program asks the user for:
- Compare two accouts (A and B)
- Guess which account has more followers

# How the program works:
- The program imports:
  - Game data (accounts and follower counts)
  - ASCII logos for display
  - The random module
- Two random accounts are selected from the data set
- The program displays:
  - Account A's name, description and country
  - A visual 'VS'
  - Account B's details
- The user gueses which account has more followers
- The program:
  - Compares follower counts
  - Checks if the guess is correct
  - Updates the score if correct
- If the guess is correct:
  - Score increases
  - The game continues with new comparisons
-If the guess is wrong
  - The game ends.
  - Final score is displayed

# What I learnt:
- How to structure a program using functions
- How to work with dictionaries and datasets
- How to compare values and return results
- How to use while loops to keep a game running
- How to track and update a score
- How to format and display structured data
