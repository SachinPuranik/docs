# Important Commands
This page is collection of commands which a developer uses in his daytoday life. I have personally switch too many times between different commnds from different tools. Hence a collection for myself. May help everyone as well.

### Git Commands

```git
$ git pull origin master , pull the master branch from origin server
$ git add --all, Add all or selective files to git
$ git commit -m "Message" , Commit git changes locally with comments
$ git push  [origin master], pull the master branch from origin server
$ git reset --hard HEAD , discard changes and reset the local tree to HEAD.
$ git stash , stash the changes on stack
$ git stash pop , pop the stashed changes with above command.
$ git config -list
$ git remote -v 
$ git branch , list the branch
$ git branch xxx , create new branch locally
$ git push origin --delete branchname //Delete the branch on host
$ git checkout xxx , switch to branch
$ git clean -fx , to clean files from source tree
$ git clean -fd , to clean folders from source tree
$ git status , know the current status of git
$ git log , print the checkin log
$ git diff, find the diff between local chage and repo
$ git merge , if for merging the code - needs additional params to work correctly.
$ git stash show -p stash@{0} > 0.patch
$ git stash pop stash@{0}
$ git stash list
$ git stash drop stash@{0} 
```
### Docker Commands

```docker
$ docker system prune
$ docker build -t denfle/proxyapi .
$ docker volume ls
$ docker volume ls -qf dangling=true
$ docker rmi {image-name}
$ docker image list
$ docker run dockerID
$ docker container ls
$ docker push <hub-user>/<repo-name>:<tag>
$ docker run -ti example
```
Something missing? feel free to add!
