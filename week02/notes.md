1. The pwd command printed out the current working directory/folder which was my root folder.

2. ls printed all my files and directories but ls -a also prints out all the folders and files starting with '.' (period) as well.

3. The first column shows permissions.

4. It's a relative path since even though im in the root folder, i haven't started the argument path with ~/ which would technically be an absolute path starting from root folder. For right now though, it is a relative path since we are specifying the path from a specific folder rather than explicitly specifying the path starting from the root folder.

5. mv moved the newly copied file README-backup.md to another folder and also renamed the file README-backup.md to old-readme.md by technically moving the file into its own folder with just a new name.

6. 3.

7. /opt/homebrew/bin/python3.

8. It's different since he is on a windows and im on a mac laptop and the windows path files are stored in a different folder. Also he didn't install python through homebrew, like i did.

9. "zsh: command not found: pyton3"... It means zsh can’t find pyton3 in my PATH; I likely meant to type python3.

10. Plain ls doesn't print out names of files and directories starting with a '.' (period). ls -a does do that though and that's why we see .venv printed when we run that.

11. My "prompt" starts with a (.venv) because something within the .venv folder's bin folder's activate script made it so that my terminal's prompt starts with a (.venv) such that it is easy to see that i'm running commands from my virtual environment.

12. It's not the same as in q7; it is a different path. This is because running source .venv/bin/activate modifies my active shell session's PATH. And it also makes it so that commands like python3 and pip3 work point to my venv instead of global environment.

13. When we ran pip list again, this time it showed the pip installation of requests and all of its dependencies as a list as compared to the first time we ran the command in which it listed nothing because pip hadn't installed anything.

14. It's back to /opt/homebrew/bin/python3, which is at my normal global normal environment PATH.

15. ls -h prints out sizes in kilobytes, terabytes, etc to make it human readable but its most useful with ls -l (together they will become -lh) because that actually lists the sizes and other stuff of ALL the entries and directories in the folder.

16. The main difference is that Ctrl+C stops or interrupts a running program, while Ctrl+D tells the program that input has finished or closes the shell.
