# WordleGuesser

This program will play out a game of wordle by guessing the most likely words based on letter frequency.

Letter frequncy is calculted based on the wordle word list and the likelihood of each word is then calculated based on the total frequency of its letters.

The regular wordle rules are followed but the solver will always use known yellow letters in guesses (as it should). This is like playing wordle with hard mode enabled. It's a "bumb" approach - no advanced strategies are used.

This method produces a 94% win rate at the game getting the answer in 4 guesses on average.

Fun fact: **alter** is the best starter word for wordle according to letter frequency.

You can play Wordle [here](https://www.powerlanguage.co.uk/wordle/)
