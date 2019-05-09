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
* `git status` to observe changes
* `git add -A` to add new files to local repo
* Commit all these changes at once with `git commit -a -m "message"`
5. Observe git logs
* `git log` will display all changes in reverse chronological order i.e. last in first out, along with hashkey, timestamps and authors.
6. Branching
* master branch is the made branch in git
* It's advisable to work on branches of master - the master branch has all production level code
* Make edits to your 'copy' of the master branch
* `git status` will show which branch you currently are working on/with. It should be displaying "On branch master"
* `git branch <branch-name>` to add a new branch
* `git status` will still display "On branch master"
* `git checkout <branch-name>` to go to new branch
* `git status` now displays "On branch <branch-name>
* Make changes in local repo -- created new files and edited this README.md.
* Typing `ls` in terminal will show these new files in directory
* Reverting to master branch with `git checkout master` will not display these new files -- thus ensuring what we wanted with Branching (didn't seem to work in Windows!?)
7. Merging
* Combining changes from various branches into master is called merging
* Go to destination branch i.e. master with `git checkout master` and then merge using `git merge <branch-to-merge-name>`
* `git merge <branch-tomerge-name>` after every change made to branch if it is to be reflected in the master branch
* `git pull` - pulls all files from remote repo to local repo
* `git fetch` - pulls all files from remote repo to local repo but in a different match
* So `git pull` = `git fetch` + `git merge`
8. 