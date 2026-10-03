1. --global means the name and email are saved for my whole computer, not just one repository. If I left it out, it would only work for the repository I was in.

2. .git showed up in ls -a but not in ls because it is hidden. It is the folder Git uses to keep the history of my project.

3. Git offered to track 2 things: lab01-log.txt and week02/. Nothing in the list was code I did not write. .venv/ was not in the list at all.

4. Nothing disappeared from the list. The only change was that .gitignore was added to it, because I had just created it.

5. It should be committed. .gitignore is a file Git tracks, so it has to be committed like the others.

6. README.md moved from "Untracked files" to "Changes to be committed". In the three-places model it went from the working folder to the staging area.

7. Git printed [master (root-commit) 4388021] Lab work so far. It said 4 files changed, 101 insertions.

8. The first seven characters (4388021) are the short commit ID, also called the hash. They are used to point to that exact commit.

9. The four steps were git status to see what changed, git add to stage the file, git commit to save it, and git log --oneline to see the commits.

10. README.md has a special name and place because GitHub shows it on the front page of the repository. It is the first thing a visitor sees.

11. gh auth login logged me in to GitHub through the browser and saved my login on my computer. Git can now push without asking for a password.

12. The front page shows my files, and below them the README shown as formatted text (Coding Café, Lab work for Coding Café, FM102). GitHub shows README.md there because it is the file that introduces the project.

13. No. git log --oneline showed the same three commits with the same codes after the push. The only new thing was origin/main next to the latest commit. The label changing from master to main came from git branch -m main, not from the push.

14. A private repository exists on GitHub, but only I and the people I invite can see it. If it did not exist on GitHub at all, there would be nothing online to share with the TAs.
