```
# A note to remind me how to sync merge with upstream repo.  
# https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

$ git fetch upstream
$ git checkout master 
# sync with upstream master while keeping local changes...
$ git merge upstream/master
# local repo is now sync, now push to remote...
$ git push origin master

```
