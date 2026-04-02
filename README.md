Git and GitHub Essentials
This repository serves as a practical guide to understanding Version Control Systems (VCS), Git, and GitHub workflows.
1. What is Version Control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. For web developers, it is essential for:
Tracking code history.
Reverting to previous stable states if a bug is introduced.
Collaborating with other developers without overwriting each other's work.
2. Git vs. GitHub: The Difference
Git: A local software/tool installed on your computer. It is the engine that tracks changes in your code.
GitHub: A cloud-based hosting service that lets you manage Git repositories online. It provides a graphical interface and tools for collaboration like Pull Requests.
3. GitHub Alternatives
If you are looking for alternatives to GitHub, here are three popular options:
GitLab
Bitbucket
Azure DevOps
4. Git Fetch vs. Git Pull
git fetch: Downloads the latest changes from the remote repository to your local machine but does not merge them into your working files. It allows you to see what others have done before deciding to integrate it.
git pull: A combination of git fetch and git merge. It downloads the changes and immediately tries to update your local branch with those changes.
5. Git Rebase
Concept: Rebase is the process of moving or combining a sequence of commits to a new base commit. In simple terms, it "rewrites history" by taking your changes and placing them on top of the latest changes from another branch, making the project history linear and cleaner.
Command:git rebase <branch-name>
6. Git Cherry-pick
Concept: Cherry-picking allows you to pick a specific commit from one branch and apply it onto another. It is useful when you want a single bug fix or feature from a different branch without merging the entire branch.
Command:git cherry-pick <commit-hash>