## <h2 align="center">Git Branching And Merging All You Need To Know.  </h2>

| Commands | Description |
| ------- | ----------- |
| **`git branch`** | List of branches (the asterisk indicates the present working branch) |
| **`git branch -a`** | List all branches (local and remote) |
| **`git branch` _`[Branch_name]`_** | To create a new branch |
| **`git branch -d` _`[Branch_name]`_** | Delete a branch |
| **`git push origin --delete` _`[branch name]`_** | Delete a remote branch |
| **`git checkout -b` _`[Branch_name]`_** | Create a new branch and switch to it |
| **`git checkout -b` _`[Branch_name]`_ `origin/`_`[branch name]`_** | Clone a remote branch and switch to it |
| **`git branch -m ` _`[Old_branch_name] [new branch name]`_** | Rename a local branch |
| **`git checkout` _`[Branch_name]`_** | Switch to a branch |
| **`git checkout -`** | Switch to the branch last checked out |
| **`git checkout --` _`[file_name.md/css/html/js/text]`_** | Discard changes to a file |
| **`git merge` _`[Branch_name]`_** | Merge a branch into the active branch |
| **`git merge` _`[Source_branch] [target branch]`_** | Merge a branch into a target branch |
| **`git stash`** | Stash changes in a dirty working directory |
| **`git stash clear`** | Remove all stashed entries |