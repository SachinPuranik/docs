# Important Commands
It is a collection of commands that a developer uses on a daily basis. I have personally switched between different commands from different tools too many times.
Hence a collection for myself. It may help everyone else as well.

There are short or no comments on this page, as that would be too much clutter. This page is intended for developers who are familiar with these commands.


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

```
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
### Docker Compose
For docker compose to work it's mandatory to have docker-compose.yml on root.

```
$ docker-compose up
$ docker-compose down
```

### KubeCtl Commands (kubernetes)

[kubernetes Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

```
$ kubectl apply -f confluance-pvc.yaml //permanent volume claim
$ kubectl apply -f confluance-pv.yaml //permanent volume
$ kubectl apply -f  ingress.yaml //ingress yml
$ kubectl delete pv {pv-name}
$ kubectl delete pvc {pvc-name}
$ kubectl get pod
$ kubectl describe pod  {pod-name}
$ kubectl apply -f ./deployment.yml -n proxyapi
$ kubectl delete -f ./deployment.yml -n proxyapi
$ kubectl port-forward --namespace default svc/my-postgresql 5433:5432
$ kubectl exec --stdin --tty {pod-name} -- /bin/bash //Open bash
$ kubectl exec --stdin --tty {pod-name} -- /bin/bash (mysqladmin status -uroot -p"${MYSQL_ROOT_PASSWORD}) //Open bash and run command
```
Something missing? feel free to add!
