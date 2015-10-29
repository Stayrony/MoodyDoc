commit
======

First, remove the commit on your local repository. You can do this using git rebase -i . For example, if it's your last commit, you can do git rebase -i HEAD~2 and delete the second line within the editor window that pops up. Then, force push to GitHub by using git push origin +master .
