# Bagian A THT RSC 2026
By 13224045 Muhammad Zaki Azzamy Syauqi

## Source Control Management

### 4 Commands in Git and Use Example
* `git commit -m "<commit title>"`: [[1]](https://github.blog/developer-skills/github/top-12-git-commands-every-developer-must-know/) to record changes of the project in Git history. It records the changes in files that are in the "staging area". A staging area is basically the files where the changes are tracked/looked for, files that have been `git add`'ed [[2]](https://www.w3schools.com/git/git_staging_environment.asp?remote=github). Example: ![Image of git commit](../lampiran/o_git_commit.png)

* `git merge <y>`: [[3]](https://www.atlassian.com/git/tutorials/merging-vs-rebasing) creates a new merge commit in x branch from y branch that ties together both histories. ![Visual of merge](https://dam-cdn.atl.orangelogic.com/AssetLink/7os54cp0428056fttsdqd133b70ih5d0.svg)
Example: ![Image of git merge]()

* `git rebase <y> <x>`: [[3]](https://www.atlassian.com/git/tutorials/merging-vs-rebasing) moves new entire/non duplicated commits of x branch on top of commits in y branch, making a linear and much cleaner history in branch x. ![Visual of rebase](https://dam-cdn.atl.orangelogic.com/AssetLink/gqe7n21k386111855w8e764rcb3qh63e.svg)
Example: ![Image of git rebase]()

* `git log`: show list of commits in current branch's history [[4]](https://education.github.com/git-cheat-sheet-education.pdf). Example: ![Image of git log](../lampiran/o_git_log.png)

### Git and VSCode Integration with GitHub
![Image of Source Control](../lampiran/source_control.png)