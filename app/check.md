# --------------------
# | [The Odin Project](http://www.theodinproject.com/home) |
# --------------------

## Ruby Programming >> Intermediate Ruby >> Project: OOP

### [Project 2: Mastermind](http://www.theodinproject.com/ruby-programming/oop)

Task:

Build a Mastermind game from the command line where you have 12 turns to guess the secret code, starting with you guessing the computer's random code.

1. Think about how you would set this problem up!
2. Build the game assuming the computer randomly selects the secret colors and the human player must guess them. Remember that you need to give the proper feedback on how good the guess was each turn!
3. Now refactor your code to allow the human player to choose whether she wants to be the creator of the secret code or the guesser.
4. Build it out so that the computer will guess if you decide to choose your own secret colors. Start by having the computer guess randomly (but keeping the ones that match exactly).
5. Next, add a little more intelligence to the computer player so that, if the computer has guessed the right color but the wrong position, its next guess will need to include the color somewhere. Feel free to make the AI even smarter.

##---------------------------
##| [Wikipedia -> Mastermind](http://en.wikipedia.org/wiki/Mastermind_%28board_game%29) |
##---------------------------

>The game is played using:
>
>*a *decoding board*, with a *shield* at one end cover a row of four large holes, and twelve (or ten, or eight, or six) additional rows containing four large holes next to a set of four small holes;
>**code pegs* of six ... different colors, with round heads, which will be placed in the large holes on the board; and
>**key pegs*, some colored or black, some white, which are flat-headed and smaller than the code pegs; they will be placed in the small holes on the board.
>
>The two players decide in advance how many games they will play, which must be an even number. One player becomes the *codemaker*, the other the *codebreaker*. The codemaker chooses a pattern of four code pegs. Duplicates are allowed, so the player could even choose four code pegs of the same color. The chosen pattern is placed in the four holes covered by the shield, visible to the codemaker but not to the codebreaker.
>
>The codebreaker tries to guess the pattern, in both order and color, within twelve (or ten, or eight) turns. Each guess is made by placing a row of small code pegs on the decoding board. Once placed, the codemaker provides feedback by placing from zero to four key pegs in the small holes of the row with the guess. A colored or black peg is placed for each code peg from the guess which is correct in both color and position. A white key peg indicates the existence of a correct color code peg placed in the wrong position.
>
>If there are duplicate colors in the guess, they cannot all be awareded a key peg unless they respond to the same number of duplicate colors in the hidden code. For example, if the hidden code is white-white-black-black and the player guesses white-white-white-black, the codemaker will award two colored key pegs for the two correct whites, nothing for the third white as there is not a third white in the code, and a colored key peg for the black. No indication is given of the fact that the code also includes a second black.
>
>Once feedback is provided, another guess is made; guesses and feedback continue to alternate until either the codebreaker guesses correctly, or twelve (or ten, or eight) incorrect guesses are made.
>
>The codemaker gets one point for each guess the codebreaker makes. An extra point is earned by the codemaker if the codebreaker doesn't guess the pattern exactly in the last guess. (An alternative is to score based on the number of colored key pegs in place.) The winner is the one who has the most points after the agreed-upon number of games are played.
>