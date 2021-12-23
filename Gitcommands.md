## **Git status** 
_The Git status command gives us all the necessary information about the current branch._
```
git status
```
We can gather information like:

*  Whether the current branch is up to date
* Whether there is anything to commit, push or pull
* Whether there are files staged, unstaged or untracked
* Whether there are files created, modified or deleted
-----

## **Git add**
_When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations)._

_We need to use the git add command to include the changes of a file(s) into our next commit._
* To add single file:
```
git add <file>
```
To add everythink at once:
```
git add -a
```
**Important: The git add command doesn't change the repository and the changes are not saved until we use git commit.**

----

## **Git commit**
_This is maybe the most-used command of Git. Once we reach a certain point in development, we want to save our changes (maybe after a specific task or issue).
Git commit is like setting a checkpoint in the development process which you can go back to later if needed.
We also need to write a short message to explain what we have developed or changed in the source code._
```
git commit -m "commit message"
```
**Important: Git commit saves your changes only locally.**

---

## **Git push**

_After committing your changes, the next thing you want to do is send your changes to the remote server. Git push uploads your commits to the remote repository._
```
git push <remote> <branch-name>
```
_However, if your branch is newly created, then you also need to upload the branch with the following command:_
```
git push --set-upstream <remote> <name-of-your-branch>
```
or

```
git push -u origin <branch_name>
```
---

## **Git pull**
_The git pull command is used to get updates from the remote repo. This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge)._

```
git pull
```
---
## **Git branch**
_Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing and deleting branches._

**Creating a new branch:**
```
git branch <branch-name>
```
---





















