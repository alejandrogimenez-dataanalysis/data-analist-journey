\# Learning Log



\## Week 1 — Git basics



Today I learned the core Git workflow: clone, edit, add, commit, push.



\- `git clone` copies a repository from GitHub to my local machine. I only need to do this once per project. Editing a file only changes my local copy. GitHub doesn't know about it yet.



\- `git add <file>` stages the file, marking it as ready to be included in the next commit.



\- `git commit -m "message"` saves a snapshot of the staged changes, with a short description of what changed. This is saved locally.



\- `git push` sends my local commits to GitHub, syncing both copies.



Local and remote repositories are independent until I explicitly sync them with push. This means I can experiment freely on my machine — if something

breaks, I can always go back to a previous commit.

