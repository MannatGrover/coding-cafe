1. Where am I?

1. pwd printed the current working directory path. It stands for print working directory.
2. ls -a prints the hidden files and directories as well which start with a dot for example .bashrc etc. ls doesnt show hidden files.
3. ls -l stands for long listing.(drwxr-xr-x 4 mannat mannat 4096 Aug 27 10:41 coding cafe) 
    d is for directory, rwx means the owner mannat can read write and execute. rx means mannat(the people with access to this) can read and execute but not change.
    4 means the path ways or the subdivisions directing to that folder.
    4096 is the file size of the folder.
    and then there is last modification date and time.

2. Build the Folder
   4. It works because coding-cafe/week02 is a relative path. It starts looking from my current folder instead of the absolute root system.


3. Move,copy, rename, delete
   5. mv did two different jobs which were to rename and move the file.


4. Where does the shell find things?
   6. currently there are 21 folders including python 3.14 in my PATH
   7. python3 lives in /usr/bin/python3
   8. It doesn't have to necessarily be the same because there are different directories depending on the interface being used.
   9. The shell searched every folder listed in the PATH but found no such executable file hence "command not found" and offered to autocorrect the command "Did you mean python3"?

5. A box of your own
   10. .venv did not appear with the plain l command because it's a file starting with . as in '.venv' which means it is considered a 'hidden file'.
   11. Everything remains same except we get a (.venv) before the PATH in the interface to show that we are in our created virtual environment. 
   12. Yes it is different since it is now in my coding cafe folder. Activate changed the path of the python3 from global to local.
   13. The first time pip list shows the few packages installed in my virtual environment. When we write pip install requests, it installs a library called 'requests in the virtual environment and then pip list lists out the packages that have now been installed. 
   14. After de-activating python3 again is back into usr/bin/python3 (the original PATH)

6. Read a manual
   15. ls -h works like ls, just lists out all the directories. But when paired with -l as in ls -lh it gives the file sizes along with the date and time of their last modification.
   16. Ctrl+C interrupts the current line(shows 'KeyboardInterrupt') and erases whatever was written in that line and moves to a fresh line >>>
       Ctrl+D sends an 'End of File' symbol and completely closes the python shell and exits back out to the regular terminal($)  
