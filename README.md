# Today's Lecture Note
### GIT COMMANDS - 2
---
$ git rm <file_Name> : Can delete files from both the local directory and the git repository
$ git rm --cached <file_Name> : Can keep files in the local directory and delete them only from the repository
$ git mv <Original_Name> <Name_to_modify> : Renaming files in repository
$ git log : Can check the all commit history of the current branch
$ git reset HEAD <File_Name> : Change a specific file to an unstage state
$ git restore <File_Name> : Can restore a specific file to HEAD commit
$ git restore --staged <File_Name> : Unstaging the file in the staging area
$ git remote add <NAME> <remote repository URL> : Register remote repository with local repository