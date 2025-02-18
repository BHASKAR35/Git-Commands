------*Common Git Commands*------
To check the status of your working directory -----------> git status
To initialize a new Git repository -----------> git init
To clone a git repository -----------> git clone url
To add files to the staging area -----------> git add . or git add file_name
To commit changes with a message -----------> git commit -m "Commit message"
To create a new branch -----------> git checkout -b branch_name
To list all branches -----------> git branch
To switch to another branch -----------> git checkout branch_name
To merge a branch into the current branch -----------> git merge branch_name
To delete a branch -----------> git branch -d branch_name
To add a remote repository -----------> git remote add alias url
To push code to a remote repository -----------> git push remote branch or git push
To fetch and merge changes from a remote repository -----------> git pull
To fetch updates from a remote repository -----------> git fetch remote
To remove a file and stage its deletion -----------> git rm file_name
To rename/move a file and stage the change -----------> git mv old_name new_name
To view commit history -----------> git log
To view differences in unstaged files -----------> git diff
To view differences in staged files -----------> git diff --staged
To temporarily save uncommitted changes -----------> git stash
To apply the last stashed changes -----------> git stash pop
To discard the last stashed changes -----------> git stash drop
To reset the working directory to the last commit -----------> git reset --hard
To undo the last commit while keeping changes -----------> git reset --soft HEAD~1
To set a global ignore file -----------> git config --global core.excludesfile .gitignore
To create a pull request -----------> Go to GitHub → Select your branch → Click "Compare & pull request"
