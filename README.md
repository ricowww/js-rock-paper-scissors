# js-rock-paper-scissors
Game of rock-paper-scissors with computer using javascript as a project for the odin project


PLAN
-------------
GUI
-command line

INPUTS

-players choice of rock, papper, scissors
-computer's choice of rock, paper, scissors
-program records scores
-program records round number

OUTPUTS

-choice of user and computer and who wins per round

PROCESSES

-Prompt user to give input rock, paper, or scissor
--Prompt function for user to input and store it in a variable
 ---Checker function to make input case-insensitive
 
-Get computer player to input random  rock, paper, or scissor
--Random function for computer to choose any of three numbers
--Numbers are converted into rock, paper, or scissors
--Store choice in a variable

-Determine who wins for the round and record the score
--if user chose rock and computer chose scissor, user gets +1 point
--if user chose rock and computer chose paper, computer gets +1 point
--if user chose rock and computer chose rock, nothing happens
--if user chose paper and computer chose scissor, computer gets +1 point
--if user chose paper and computer chose paper, nothing happens
--if user chose paper and computer chose rock, user gets +1 point
--if user chose scissor and computer chose scissor, nothing happens
--if user chose scissor and computer chose paper, user gets +1 point
--if user chose scissor and computer chose rock, computer gets +1 point

-Keep track of round
--add +1 to round after the function above
---round starts at a value of 0

-Repeat above until round 5
--if round is less than 5, repeat all these functions
--if round is not less than 5, declare the winner
---if user points higher than computer points, user wins and gets a congratulations message
---if computer points higher than computer points, computer wins and gets a congratulations message
---if user and computer score is the same, no one wins and gets a draw message


