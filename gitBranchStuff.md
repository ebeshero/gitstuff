# On Working in Branches: Observations
## Maintaining Local Branches 
You can maintain a local branch that isn't pushed to remote with git add and git commit. 
Mysteriously, if you use git add in your branch, the files are "added" to your master branch as well. But once you commit in your local branch, the added files disappear from the master branch.

To select just a single file you want from the local branch to merge into master, follow these instructions (using git checkout filepath):
http://jasonrudolph.com/blog/2009/02/25/git-tip-how-to-merge-specific-files-from-another-branch/

