# easyAI-Project-One
easyAI for checkers game in Python
this is Intro AI class project 1
implement four functions:
make_move()
lose()
is_over()
scoring()

How to win:
the game can be won whenthe opponnet is unable to make a move.This can be done in two ways: 
The entirety of a player's pieces was captured by the opponent(when the piece is a king).

When beginning the coding process, we decided to make a AI vs AI code, and to scan the 
given code and see what the simplest function would be to take down first. And we landed on the 
is_over() and scoring() functions. And the easyAI code(s) (Tic-Tac-Toe and Connect Four) 
provided to us in the second part of the assignment were useful hints or previews of possible 
ways to complete the checker's game. Specifically, Micaela had the brilliant idea to look back at 
those codes to check over and understand how they accounted for scoring and how to tell if the 
game was officially over. In the end, Micaela decided those codes were most suitable for helping 
in building to the completion of the checkers game, uncovering those solutions when coding our 
two functions: is_over() and scoring().

Moving on to our last two functions, we surprisingly had difficulty figuring out how to 
code the make_move() and lose() functions. 
To elaborate, we decided that the best course was to try and build the move() function. It 
was a frustrating experience until Micaela got an idea from a Teaching Assistant (TA) to look at 
the test_checkers file/program for inspiration and guidance. And from the test_checkers file, we 
developed an idea of where to start the move function, but we foolishly could not figure out how 
to finish it. And it showed very clearly when we ran the program. Where pieces were supposed 
to move, they stayed in their original positions 999 turns later. Or, if any game piece of the 
checkerboard would shift forward the progress made would not be remembered, nor its array 
updated. So, we were left delaying its progress and skipping it for the day or moment.

Once everything was in order, Stephanie decided to take the training wheels off and put it 
into the original code to see if it would work out. And for the most part, the updated lose 
function seemed to run just fine and did not run into any particular errors. However, the list 
(players' positions) that was supposed to make the code work and update was obviously not 
working. The move function still seemed incomplete, as the game pieces' positions and 
arrangements refused to update. So, we had to go back to the drawing board to see what was 
causing it.
We finally went back to the move function and decided to snoop through the 
test_checkers file again to see how they updated their array to get the code to work. And so, we 
went in loops to figure out how the code updated the player's positions list once a game piece 
made a move. Hence, Stephanie utilized the commented board layout to try and envision what 
the move function was trying to achieve, keep track, and rationalize shifting made in the 
unfinished code.
