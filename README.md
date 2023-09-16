# Git Commands
Some of the commonly used git commands.


## Get & Create Projects
|Command                         |Description                                                      |
| -------------                  |:-------------:                                                  |
| git clone [repository-url]     | Create a local copy of your remote repository  on your computer |
| git init                       | Initialize a local repository on your computer                  |


## Branch
|Command                                            |Description                                                 |
| -------------                                     |:-------------:                                             |
| git branch                                        | List branches                                              |
| git branch [branch-name]                          | Create a new branch                                        |
| git branch -d [branch-name]                       | Delete a branch                                            |
| git checkout -b [branch-name]                     | Create a new branch and switch to it                       |
| git checkout [branch-name]                        | Switch to given branch                                     |
| git branch -m [old-branch-name] [new-branch-name] | Rename a local branch                                      |
| git branch -m [new-branch-name]                   | Rename a branch _**after switched to it**_ (active branch) |
| git switch -c [branch-name]                       | Create a new branch and switch to it                       |
| git switch [branch-name]                          | Switch to given branch                                     |


## Merge
|Command                                     |Description                                    |
| -------------                              |:-------------:                                |
| git merge [branch-name]                    | Merge the given branch into the active branch |
| git merge [source-branch] [target-branch]  | Merge the source branch into target branch    |


## Share & Update Projects
|Command                                     |Description                                                           |
| -------------                              |:-------------:                                                       |
| git remote add origin [repository-url]     | Add a new remote repository                                          |
| git push origin [branch-name]              | Update the given remote branch with local commits                    |
| git push -u origin [branch-name]	         | Useful when pushing a new branch, adds upstream (tracking) reference |
| git pull                        	         | Update the local repository from the corresponding remote repository |


## Snapshooting
|Command                                 |Description                                                                                                                    |
| -------------                          |:-------------:                                                                                                                |
| git status                             | Display the state of the repository and staging area (see the tracked, untracked files and changes)                           |
| git add [file-name]                    | Add a file to the staging area                                                                                                |
| git add .                              | Add all new and changed files (_**entire directory**_) to the staging area _**including files whose names begin with a dot**_ |
| git add *                              | Add all new and changed files (_**entire directory**_) to the staging area _**excluding files whose names begin with a dot**_ |
| git commit -m "[your commit message]"  | Capture a snapshot of the project's currently staged changes (commit changes)                                                 |


## Inspection & Comparison
|Command                                                 |Description                                                                              |
| -------------                                          | :-------------:                                                                         |
| git log                                                | Display the history of committed changes                                                |  
| git log -[int]                                         | Display the limited number of commits, starting with the most recent commit             |
| git log --after="[yyyy-mm-dd]"                         | Display all commits made after the given date                                           |
| git log --before="[yyyy-mm-dd]"                        | Display all commits made before the given date                                          |
| git log --after="[yyyy-mm-dd]" --before="[yyyy-mm-dd]" | Display all commits within a range of dates                                             |
| git log --author="[author-name]"                       | Display commits only made by a specific author                                          |
| git log --oneline                                      | Display each commit's log data on a single line briefly (_**only the commit message**_) |
| git diff                                               | Display the changes between your current working directory and your staging area        |

