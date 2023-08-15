# Git Commands 

| Command                                                    | Description                                        |
| ---------------------------------------------------------- | -------------------------------------------------- |
| `git clone <repo_link>`                                    | clones the repository with link                    |
| `git add .`                                                | adds all files to git                              | d |
| `git add <file_path>`                                      | adds a single file to git                          |
| `git commit -m "<commit_message>"`                         | commit with given message                          |
| `git commit --amend`                                       | update commit                                      |
| `git push -f`                                              | forced push (needed after git commit --amend)      |
| `git pull --rebase origin <branch_name>`                   | rebase with the remote branch                      |
| `git rebase -i HEAD~<number_of_commit>`                    | rebase commits                                     |
| <h2>Change Branch Name</h2>                                |                                                    |
| `git brnach -m <new_branch_name>`                          | changes branch name in local                       |
| `git push origin -u <new_branch_name>`                     | push new branch to git                             |
| `git push origin --delete <old_branch_name>`               | delete remote old branch                           |
| <h2>Branch </h2>                                           |                                                    |
| `git checkout <branch_name>`                               | changes branch                                     |
| `git checkout -b <new_branch_name>`                        | create a new branch with changes in current branch |
| `git push origin:<local_branch_name>:<remote_branch_name>` | push local branch with different branch name       |
| `git fetch --all`                                          | get all info about branches                        |
| `git branch`                                               | list all branches in your local                    |
| `git branch --all`                                         | list all branches both in local and remote         |