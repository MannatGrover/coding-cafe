1. --global means the name and email are saved for my whole computer, not just one repository. If I left it out, it would only work for the repository I was in.

2. .git showed up in ls -a but not in ls because it is hidden. It is the folder Git uses to keep the history of my project.

3. Git offered to track 2 things: lab01-log.txt and week02/. Nothing in the list was code I did not write. .venv/ was not in the list at all.

4. Nothing disappeared from the list. The only change was that .gitignore was added to it, because I had just created it.

5. It should be committed. .gitignore is a file Git tracks, so it has to be committed like the others.

6. README.md moved from "Untracked files" to "Changes to be committed". In the three-places model it went from the working folder to the staging area.

7. Git printed [master (root-commit) 4388021] Lab work so far. It said 4 files changed, 101 insertions.

8. The first seven characters (4388021) are the short commit ID, also called the hash. They are used to point to that exact commit.
