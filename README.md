# cse210-01
Repository for Tic-Tac-Toe Game created for CSE 210 Programming with Classes

This game was created by following a tutorial for a project by TechVidvan, found at the following url:
https://techvidvan.com/tutorials/python-game-project-tic-tac-toe/

I initally found the game on the following git repository:
https://github.com/ganeshkavhar/Python-Tic-Tac-Toe-Game
but I didn't fully understand the code until I found the tutorial, which
explained everything. 

Here is the summary of the project, as found on the TechVidvan website:
"With this project in Python, we have successfully made the Tic Tac Toe game. 
We used the popular pygame library for rendering graphics on a display window. 
We learned how to capture events from the keyboard or mouse and trigger a 
function when the mouse button is pressed. This way we can calculate mouse 
position, draw X or O on the display and check if the player wins the game or not. 
I hope you enjoyed building the game."

I started the project by adding a new git repository on github and creating a .gitignore
file in order to establish the Initial Commit. Then I opened Python and began
entering code as I followed along reading the tutorial.

After I finished entering all of the code from the tutorial and git repo, I found that it 
would render the opening image and the game board, but did not respond to mouse clicks to 
draw X's and O's on the board. After some study, I noticed a small error in one line 
of the original code from the git repo, "elif event.type is MOUSEBUTTONDOWN:" 
At first I tried switching the command to MOUSEBUTTONUP, but there was no difference. 
Then I realized that "is" needed to be changed to "==" and then the game worked perfectly.

I made this game my own by choosing my own colors, creating all my own images from scratch,
rewording the messages to suit my taste, and creating a function, "draw_cat" to add the large 
"Cat Scratch!" letter C across the board when the game ends in a draw.

Once I had the game working to my satisfaction, I used the Source Control features on VS Code
to upload my files to my github repository.

Upon reviewing the requirements for the assignment, I realize that there is supposed to be
a function called "main." I will continue to work on the game to make sure that it
complies with all the requirements before the due date at the end of this week.
