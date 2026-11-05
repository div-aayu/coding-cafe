1. The pwd command printed out the current working directory/folder which was my root folder.

2. ls printed all my files and directories but ls -a also prints out all the folders and files that were hidden ('.' files)

3. The first column shows permissions.

4. it works because the folder 'coding-cafe' is already in the root folder(where i currently am) it is a relative path since we are specifying the path from a specific folder rather than explicitly specifying the path starting from the root folder.

5. mv moved the newly copied file README-backup.md to another folder and also renamed the file README-backup.md to old-readme.md by technically moving the file into its own folder with just a new name.

6. 10

7. C:\msys64\ucrt64\bin\python.exe

8. It's different since she is on a mac and im on a windows laptop and files are stored in a different location on our laptops

9. pyton
  + CategoryInfo          : ObjectNotFound: (pyton:String) [], CommandNotFoundException
  + FullyQualifiedErrorId : CommandNotFoundException
This means the shell could not find pyton in any of the folders listed in the path.

10. ls doesn't print out names of hidden files and directories. ls -a does do that though and that's why we see .venv printed when we run that.

11. My "prompt" starts with a (.venv) because something within the .venv folder's bin folder's activate made it so that my terminal's prompt starts with a (.venv) such that it is easy to see that i'm running commands from my virtual environment.

12: No, the paths are different. This tells me that Activate.ps1 changed my PATH so that python is found inside .venv

13. When we ran pip list again, this time it showed the pip installation of requests and all of its dependencies as a list as compared to the first time we ran the command in which it listed nothing because pip hadn't installed anything.

14. It's back to /opt/homebrew/bin/python3, which is at my normal global normal environment PATH.

15: -Recurse shows us all the subfolders and items too instead of just the folders present in the current directory

16. The main difference is that Ctrl+C stops or interrupts a running program, while Ctrl+D tells the program that input has finished or closes the shell.
