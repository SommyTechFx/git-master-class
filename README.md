# git-master-class
Git and Version Control

**Explain version control.**

Version control is a system that tracks changes to files over time, maintaining a history of different versions. It enables collaboration by allowing multiple contributors to work on a project concurrently. Key components include repositories (storage for project files), commits (record of specific versions), branching (creating separate lines of development), merging (combining changes from different branches), checkout (switching to a specific version), and conflict resolution. Remote repositories, hosted on servers, facilitate collaborative development. Git is a popular version control system. Overall, version control ensures organized and efficient management of project development.


**Explain difference between git and github**

>Git
1. Git is a distributed version control system that allows individuals or teams to track changes in source code during software development.

2. Git It manages and tracks changes to files in a repository, enables branching and merging, and provides tools for version control locally on a user's machine.

3. Git is used for version control in both local and distributed (team-based) development environments.


>GitHub

1. GitHub is a web-based platform that provides hosting services for Git repositories.

2. It extends Git by offering a centralized location for hosting, sharing, and collaborating on Git repositories. GitHub adds features like issue tracking, pull requests, and collaboration tools.

3. GitHub is used for remote repository hosting, collaborative development, and social coding. Developers can push their Git repositories to GitHub for others to access and contribute.


**List 3 other github alternatives**
1. GitLab
2. Bitbucket
3. SourceForge



**Explain the difference between git fetch and git pull,**

<git fetch:>
 command is used to retrieve changes from a remote repository to your local repository. It fetches the latest commits from the remote but does not automatically merge them into your working branch.


<git pull:>
 command on the other hand, is a combination of git fetch and the merge operation. It fetches the changes from the remote repository and automatically merges them into the current branch.


**Explain in simple terms git cherry-pick and the command for it**

Git cherry-pick: is a Git command that allows you to pick and apply specific commits from one branch and apply them onto another branch. This is useful when you want to selectively choose and include specific changes without merging entire branches.


Command: git cherry-pick <commit_hash>


