# js-rock-paper-scissors
Game of rock-paper-scissors with computer using javascript as a project for the odin project


PLAN
-------------
[update 2021 12 29]
Testing is hard on a long code
Lets make functions into separate codes first
Then we mishmash them together

GUI
-command line

INPUTS

-players choice of rock, papper, scissors
-computer's choice of rock, paper, scissors
-program records scores
-program records round number

OUTPUTS

-choice of user and computer and score per round
-end game message after 5 rounds

PROCESSES

-Let user input rock, paper, or scissor - OK
--function to store textbox into a variable - OK
 ---Checker function to make input case-insensitive - OK
 
-Get computer player to input random  rock, paper, or scissor - OK
--Random function for computer to choose any of three numbers
--Numbers are converted into rock, paper, or scissors
--Store choice in a variable

-Determine who wins for the round and record the score - OK
--if user chose rock and computer chose scissor, user gets +1 point
--if user chose rock and computer chose paper, computer gets +1 point
--if user chose rock and computer chose rock, nothing happens
--if user chose paper and computer chose scissor, computer gets +1 point
--if user chose paper and computer chose paper, nothing happens
--if user chose paper and computer chose rock, user gets +1 point
--if user chose scissor and computer chose scissor, nothing happens
--if user chose scissor and computer chose paper, user gets +1 point
--if user chose scissor and computer chose rock, computer gets +1 point

-Keep track of round - OK
--add +1 to round after the function above
---round starts at a value of 0


-Repeat above until round 5
--if round is less than 5, repeat all these functions
--if round is not less than 5, declare the winner
---if user points higher than computer points, user wins and gets a congratulations message
---if computer points higher than computer points, computer wins and gets a congratulations message
---if user and computer score is the same, no one wins and gets a draw message


Wrap the above code into calleable functions


Add an event trigger to call the above functions when the submit button is clicked

Convert alert messages to <p> messages

TASKS
[DONE]github repo
[DONE]html and js connector
[DONE]component codes
[CANCELLED]flowchart for game
[ONGOING]Separate files for codes
--input acceptor-rejector
--storer for user [DONE]
--AI to choose for AI [DONE]
--evaluator to see who wins round [DONE]
--round keeper to add to round and declare game over
--messages [DONE]
[DONE] TIE into submit>AI>evaluate>gameover

[DONE]semifinal code
[DONE]tie together the messages into one DIV
[ONGOING]debug


DEBUG NOTES
-trigger not working due to event listener having a "()" [DONE]
-whole code not running due to test variables causing duplicates, error spotted in console log [DONE]
-scores are not persistent, solved, see below [DONE]
-game round numbers are not persistent, solved by rewriting code and putting variables on outside and just using one function [DONE]
-invalid inputs push through up to AI by doing the thing above. An if with "return;" will cancel all the lines below [DONE]
-tried relocating the supposedly persistent variables (user scores etc.) to upper line of script, assuming the issue is about redeclaring when click calls functions [TRIED]
-tried making functions empty and calling them empty but doesnt work either [TRIED]
-tried making the alerts non concatenated, thinking that concatenations may be causing  value reset but it doesnt [TRIED]
-calling evaluatorRockPaperScissors() shows that roundMessage was not defined as a variable [DONE]
-Div not displaying text permanently [DONE]
-Note debug in every section as you go to ensure QC [TIP]
-easier to rewrite whole code than to edit debug [TIP]
-Plan, Pseudocode, Components-Debug, Whole-Debug, Rewr
ite-Debug
-FINAL code is "fullCodeV2"




----------------------


2022 01 26 We are making a UI now!



