## <h2 align="center">Git Branching And Merging All You Need To Know.  </h2>

| Commands | Description |
| ------- | ----------- |
| **`git branch`** | List of branches (the asterisk indicates the present working branch) |
| **`git branch -a`** | List all branches (local and remote) |
| **`git branch [Branch_name]`** | To create a new branch |
| **`git branch -d [Branch_name]`** | Delete a branch |
| **`git push origin --delete [branch name]`** | Delete a remote branch |
| **`git checkout -b [Branch_name]`** | Create a new branch and switch to it |
| **`git checkout -b [Branch_name] origin/[branch name]`** | Clone a remote branch and switch to it |
| **`git branch -m [Old_branch_name] [new branch name]`** | Rename a local branch |
| **`git checkout [Branch_name]`** | Switch to a branch |
| **`git checkout -`** | Switch to the branch last checked out |
| **`git checkout -- [file_name.md/css/html/js/text]`** | Discard changes to a file |
| **`git merge [Branch_name]`** | Merge a branch into the active branch |
| **`git merge [Source_branch] [target branch]`** | Merge a branch into a target branch |
| **`git stash`** | Stash changes in a dirty working directory |
| **`git stash clear`** | Remove all stashed entries |