# Rebase-Git

Rebasing is the process of moving or combining a sequence of commits to a new base commit. The primary reason for rebasing is to maintain a linear project history. Merge does the same but does not facilitate history replication.

```

1. Use the following command to create a feature branch:
$ git branch feature-one

2. Run the following command to verify the creation of the feature-one branch:
$ git branch -a

3. Switch to the feature-one branch
$ git checkout feature-one
$ git status

4. Edit files in the master branch
$ git checkout main
$ vi file.html (Edit already created file)

5. Use the following commands to commit the changes:
$ git add file.html
$ git commit -m “file modified”

6. Switch to the feature-one branch
$ git checkout feature-one

7. Use the following command to execute git rebasing:
$ git rebase --autostash main

8. Run the following command in the terminal
$ git log --oneline

```
