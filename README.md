# training
Explain Version control.
Version control is a process used in software development to track and manage changes to code over time. It allows developers to keep track of the different versions of a piece of code, and to revert back to a previous version if needed. It also makes it easy for developers to collaborate on code, as they can see the history of changes and who made them. Some popular version control systems include Git and Subversion.

Explain difference between git and github
Git is a version control system that developers use to track changes to code. It's used locally on a developer's machine. GitHub, on the other hand, is a web-based hosting service that developers use to share and collaborate on code. It uses Git under the hood, but also provides additional features like project management and issue tracking. In short, Git is the version control system, and GitHub is the online service that uses Git.

List 3 other github alternative.
1. Bitbucket.
2. GitLab.
3. SourceForge

Explain the difference git fetch and git pull.
Git fetch downloads the latest changes from a remote repository to your local repository, but it doesn't merge them into your code. Git pull does both of those things - it downloads the latest changes and then merges them into your code. In short, Git fetch gets the latest changes, while Git pull gets and applies the latest changes.

Explain in simple terms git rebase and the command for it.
Git rebase is a command that takes the changes in your local repository and replays them on top of the latest changes from the remote repository. Basically, it allows you to integrate your changes into the latest version of the code without creating a merge commit. The command for it is "git rebase." Just be aware that it can be dangerous to use, as it can cause conflicts and other issues if not done correctly.

Explain in simple terms git  cherry-pick and the command for it.
Git cherry-pick is a command that allows you to choose specific commits from a branch and apply them to another branch. It's a bit like copy and paste for Git commits. The command for it is "git cherry-pick." It's useful when you want to apply a specific commit without merging the entire branch.
