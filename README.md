# PowerShell exercise to take you from zero to hero

This is a terminal educational game to learn PowerShell through hands-on problem solving to teach the nuances of the code language. It's suitable for individual learning or as a team activity with one instructor.

## About the game
The code is written in PowerShell. The player is asked with questions that are tailored to the system that runs the code. To find the answers, the player would need to utilize new PowerShell concepts each time on his/her own that gets harder as the game progresses.
<br>For the unfamiliar with PowerShell, the game in its entirely (without the bonus questions) should take about 3-5 hours. For more advanced folks, it should take a bit less, but the bonus questions will keep them busy ;)

## How to run

The PowerShell code is compiled into an executable using [PS2EXE](https://github.com/MScholtes/PS2EXE), making it easy for players to run the game as a standalone black-box application. The executable is zipped and can be downloaded from the **Releases** section, using the password of `infected`. Some AVs may flag the executable as suspicious because of the compilation method. 
Therefore it is recommended to run it on a VM. <br>If using a VM is a problem, the game can also be run by executing `main.ps1` with `powershell.exe -f main.ps1` on any system, but the unrighteous players would be able to look at the code in plaintext and see the answers. You might need to change the execution policy first `Set-ExecutionPolicy Bypass` on an administrator PowerShell terminal. The actual game instructions are inline.

## Instructions for the instructor

The game was originally made to be facilitated by an instructor who can assist players as needed. There are some secret cheat codes to help speed things up for the instructor. To activate them, enter `powershellgod` in the terminal. The following passwords are available:
1. `omri!` - view the answers for all questions or up to a specific question ID.
2.  `skipto` - skip to a specific question.
3.  `oneq` - reveal the answer for one question.

These are great in case someone accidently exits the terminal for instance, or for any shortcut needed :)

## About the questions

The questions starts easy and gets harder with time. Each question is meant to cover a different aspect of the language. Of course it is not a comprehensive guide to learn everything about PowerShell, but the ones who finish it will probably be able to take on most scripting tasks. I haven't covered efficiency with the language nor OOP stuff, but it should be more than enough for a fun game :) 

The questions are written in a way that it is easy to understand, easy to see what is the solution for each question (in the last question the particiapants are redirected to the source code so they can take a look), and also easy to add/remove question if desired. 
I think this amount of questions is more than enough for a fun exercise, but feel free to add questions if you see it fit.

# In-game screenshots

![image](https://github.com/omrirefaeli/PowershellZeroToHero/assets/30568019/7f121af9-7bef-41a8-b254-a5d9ac9277fc)


![image](https://github.com/omrirefaeli/PowershellZeroToHero/assets/30568019/1d2e022e-d122-4cba-90f9-78b110da6440)
