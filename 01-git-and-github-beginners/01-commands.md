## Git Commands
* `git init` - Turn the current working directory into a git repository
* `git clone` - Bring a repository hosted somewhere else like GitHub into a local folder
* `git add` - Track a new file or folder. Add to file or folder to the stage, meaning they will be ready to be committed. They can be removed from the stage before committing.
* `git commit` - Save your file changes to Git version control, and the selected text editor will be opened to enter a message. Commits can be reverted/removed/deleted.
* `git commit -m "This is my commit message"` - Commit with an in-line message
* `git push` - Upload Git commits to a remote repository, such as GitHub, BitButcket, etc.
* `git push -u origin my-branch` - Upload commits to a remote repository and specify where and which branch
* `git pull` - Download changes from a remote repository, the opposite of push
* `status` - Check which files are tracked and untracked
* `git init -b main` - Initiate a repo with a named branch
* `git branch -a` - Show all branches and the current one with an asterisk
* `git checkout` - Change to another branch
* `git checkout -b my-new-branch` - Change to a new branch
* `git merge my-branch` - Merge changes from branch `my-branch` to the current working branch (usually done through a pull request in GitHub)
* `git pull -r origin my-branch` - Rebase current working branch from `my-branch`, pulling all changes that are ahead of the current working branch
* `git pull --rebase origin my-branch` - Long version
* `git test` - Test update to raise a conflict
* `git rebase --continue` - Continue the rebase once the conflicts have been solved
* `git push -f` - Force push if you know local is ahead of remote
