# Git Commands
Some of the commonly used git commands.

## Create & Get Projects
|Command                         |Description                                                      |
| -------------                  |:-------------:                                                  |
| git init                       | Initialize a local repository on your computer                  |
| git clone [repository-url]     | Create a local copy of your remote repository  on your computer |

## Branch
|Command                                            |Description                                                   |
| -------------                                     |:-------------:                                               |
| git branch                                        | List branches                                                |
| git branch [branch-name]                          | Create a new branch                                          |
| git branch -d [branch-name]                       | Delete a branch                                              |
| git checkout -b [branch-name]                     | Create a new branch and switch to it                         |
| git checkout [branch-name]                        | Switch to given branch                                       |
| git branch -m [old-branch-name] [new-branch-name] | Rename a local branch                                        |
| git branch -m [new-branch-name]                   | Rename a branch _**after switched into it**_ (active branch) |
| git switch -c [branch-name]                       | Create a new branch and switch to it                         |
| git switch [branch-name]                          | Switch to given branch                                       |


## Merge
|Command                                     |Description                                    |
| -------------                              |:-------------:                                |
| git merge [branch-name]                    | Merge the given branch into the active branch |
| git merge [source-branch] [target-branch]  | Merge the source branch into target branch    |

