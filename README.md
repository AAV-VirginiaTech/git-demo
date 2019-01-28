# git-demo

### Getting/Updating a Repo
* `git clone <url>` - Copies a repo down from the URL and creates the origin remote
* `git fetch` - Scans the origin remote for any changes, **Doesn't change any files**
* `git pull` - If there are any changes that git recognizes, it pulls down the changes locally

### Putting code in a Repo
* `git add <files>` - Adds the listed files to the staging area 
* `git commit -m` - Records any changes in the staging area as a commit in the history 
* `git push`- Sends and local commits to the associated branch at origin remote unless specified

### General Use Commands
* `git status` - Lists the current status of repo, ie: if local is ahead/behind origin by any commits
* `git checkout <branch>` - Switches to the given branch 
* `git branch` - Lists the branches that are known
* `git log` - Lists the commit history of the repo


### Other Commands
* `git log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all`
