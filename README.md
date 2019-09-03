# Constructor-Word-Guess

Game Information: This is a node.js based application with interactive prompts on the command-line. Good luck and enjoy the game!

1.The game requires `inquirer` or `prompt` npm packages.
- `Letter.js`: Contains a constructor, Letter. This constructor displays a blank placeholder depending on whether or not the user has guessed the letter.

- `Word.js`: Contains a constructor, Word that depends on the Letter constructor. This is used to create an object representing the current word the user is attempting to guess.

- `index.js`: The file containing the logic for the course of the game, which depends on `Word.js` and:

    + Randomly selects a word and uses the Word constructor to store it

    + Prompts the user for each guess and keeps track of the user's remaining guesses

2.`Letter.js` should not require any other files.

3.`Word.js` should only require `Letter.js`

#### Demo

**Start**

![command line](/image/start.PNG)

**Lose and Play again**

![command line](/image/lost.PNG)

**Win and Exit game**

![command line](/image/win.PNG)

![command line](/image/exit.PNG)
