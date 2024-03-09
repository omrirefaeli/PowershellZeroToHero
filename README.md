# Powershell exercise to take you from zero to hero

This is a terminal educational game to learn Powershell through hands-on porblem solving to teach the nuances of the code language. Can be played individually or as a team learning activity with one instructor.

## About the game
The code is written in Powershell. The player is asked with questions that are tailored to the system that runs the code. To find the answers, the player would need to utilize Powershell concepts on his/her own that gets harder as the game progresses.

## How to run

The PS code is compiled with [PS2EXE](https://github.com/MScholtes/PS2EXE), that creates an executable that the players can run as a black box. The executable is zipped and can be donwloaded at the **Releases** section, with the password of `infected`. Some AVs flag the executable as suspicious because of the way it gets compiled. 
Therefore it is recommended to run it on a VM. <br>If that is a problem and the players cannot use a VM, it is possible to run `main.ps1` with `powershell.exe -f main.ps1` on any system. You might need to change the execution policy first `Set-ExecutionPolicy Bypass` on an administrator Powershell terminal. The actual game instructions are inline.

## Instructions for the instructor

The game was originally made to be held with an instructor that can help in case the players needs it. There are some secret cheat codes to help speed things up for the instructor. To activate them, submit `powershellgod` in the terminal. These are the different passwords:
1. `omri!` - view the answers for all questions or just until a specific question ID
2.  `skipto` - skip to a specific question
3.  `oneq` - reveal the answer for one question
