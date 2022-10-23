# testing
## Testing GIT to use on a daily basis
* To clone repo run git $ clone {url}
* To stage file run command $ git add filename or use $ git add . to stage everything
* To commit changes run command $ git commit -m "Always add good explanations of changes"
* To send changes to Github use command $ git push origin master (origin - to place from which project was cloned, master = branch). Or use "Sync" button in VS CODE
* To push commits to remote repo us $ git push origin <current branch name>
* To create new branch runb $ git checkout -b <branc name>
* To rebase your branch first be in your new branch, then update git with $ git fetch -p. Then run $ git rebase origin/master:
    * If there are merge conflicts, solve then, then run $ git add . and $ git rebase --continue
    * If there are no conflict or they are solved, run $ git push origin HEAD --force-with-lease
* To not to track files with git, create a file .gitignore
* To remove cached files, run $ git rm -rf . --cached

kodel?