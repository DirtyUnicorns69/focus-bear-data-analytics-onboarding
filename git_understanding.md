##### Git (terminal / command line)

git clone <repo-url>

git branch <branch-name>

git checkout <branch-name>

git add <file>

git commit -m "message"

git push origin <branch-name>

git pull origin main



##### GitHub Desktop

the visual app



##### GitHub.dev (.)

online lightweight VS Code editor



##### Staging vs. Committing

You always have to stage (git add) changes first. Committing a branch without staging means no changes are recorded.



1. **Clone repo** → Downloads the repository to your local PC hard drive.
2. **git pull** → Updates your local repo so it matches the latest version on GitHub.
3. **Open files in VS Code** → Navigate to the repo folder and open files normally.
4. **Edit files** → Any changes are saved to your local PC (working directory).
5. **Stage changes** → Use git add (or Desktop/VS Code GUI) to select which files/lines you want in the next commit.
6. **Commit changes** → Saves the staged changes to your local branch history.
7. **Push branch** → Uploads your local branch commits to the remote branch on GitHub.
8. **Create Pull Request (PR)** → Merge your working branch into main.
9. **Approve and merge PR** → Changes from the branch are incorporated into main on GitHub.



##### Advanced Git Commands \& When to Use Them

git checkout main -- <file> → Restore a specific file from main without affecting other changes.

git cherry-pick <commit> → Apply a specific commit from another branch without merging the whole branch.

git log → View commit history and understand how changes evolved.

git blame <file> → See who last modified each line in a file and when.



##### git bisect

**binary** search tool to find the commit that introduced a bug



1. git bisect start
2. git bisect bad
3. git bisect good <hash-of-last-commit-you-know-worked>
4. git bisect reset



##### Writing Meaningful Commit Messages



##### Pull Requests


