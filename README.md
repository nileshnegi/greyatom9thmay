# greyatom9thmay
Test repository to familiarize myself with git commands.<br>
Created on 9th May 2019 (as the name suggests!)<br>
<br>
1. Create repository on github.com<br>
* Create and edit README.md<br>
* Commit changes to repo
2. Create local repo and sync
* `git init` using Git Bash on Windows
* `git remote add origin <link>` to link local repo to central repo
3. Fetch files from remote to local repo
* `git pull origin master`
* Suggested to do this everytime before starting code session
4. Pass changes from local to remote repo
* Create a new file
* `git status`
* Add this newly created file first to local repo and next push it to remote repo
* `git add <file-name>`
* `git status` to observe changes
* Commit these changes using `git commit -m "message"`
* Use `git add -A` to add multiple files
* Create some more files. Maybe modify existing files
*`git status` to observe changes
* `git add -A` to add new files to local repo
* Commit all these changes at once with `git commit -a -m "message"`