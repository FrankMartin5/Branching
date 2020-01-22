## Git Branching

 Cheat sheet for Branching

### Basic Git Commands
* `git init` - create local repo.
* `git add` - Add modified files to index (staging).
* `git commit -m "message"` - commit to local repo.
* `git status` - see status in local repo.
* `git log` - view commit log.
* `git log --oneline` - Compact view of git log
* `git remote add origin URL` - connect local repository to remote URL

### Basic Branching
* `git branch` - Show branches, current branch
* `git branch branchName` - create branch `branchName`
* `git checkout branchName` - check out the branch
* `git checkout -b otherBranch` - create and checkout `otherBranch`
* `git pull origin otherBranch` - pull remote otherBranch
* `git pull origin master` - Pull remote master into local branch to resolve conflicts
* `git push origin otherBranch` - Push local branch to Github; go to Github and create pull request.
