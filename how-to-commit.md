### How to Commit Git Changes to Docs Repo

1. `cd` into local docs folder
2. `git pull` to update local with the latest changes on GitHub
3. `git branch` should yield v0.11  in your terminal
4. If you’re not on the right branch, `git checkout v0.11`
5. Make changes to titles/descriptions and save the files
6. `git add .` 
7. `git status` to show the files that you’ve changed
8. `git commit -m "message"` to describe the changes you’ve made
9. `git push` to take your local changes and push them up to github

**Tip:** To open the folder you're in within your terminak in VS Code with the `code.`, go into VS Code, run `SHIFT + COMMAND + P` and then type in `SHELL COMMAND: Install 'code' command in Path`