# PowerShell exercise to take you from zero to hero

This is a terminal educational game to learn PowerShell through hands-on problem solving to teach the nuances of the code language. It's suitable for individual learning or as a team activity with one instructor.

## About the game
The code is written in PowerShell. The player is asked with questions that are tailored to the system that runs the code. To find the answers, the player would need to utilize new PowerShell concepts each time on his/her own that gets harder as the game progresses.

## How to run

The PowerShell code is compiled into an executable using [PS2EXE](https://github.com/MScholtes/PS2EXE), making it easy for players to run the game as a standalone black-box application. The executable is zipped and can be downloaded from the **Releases** section, using the password of `infected`. Some AVs may flag the executable as suspicious because of the compilation method. 
Therefore it is recommended to run it on a VM. <br>If using a VM is a problem, the game can also be run by executing `main.ps1` with `powershell.exe -f main.ps1` on any system. You might need to change the execution policy first `Set-ExecutionPolicy Bypass` on an administrator PowerShell terminal. The actual game instructions are inline.

## Instructions for the instructor

The game was originally made to be facilitated by an instructor who can assist players as needed. There are some secret cheat codes to help speed things up for the instructor. To activate them, enter `powershellgod` in the terminal. The following passwords are available:
1. `omri!` - view the answers for all questions or up to a specific question ID.
2.  `skipto` - skip to a specific question.
3.  `oneq` - reveal the answer for one question.
