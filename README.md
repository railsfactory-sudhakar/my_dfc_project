"helo" 
some text
GIT
[-u | --set -upstream] can use any one.
commands
config -l | -get user.name | add user.name "username" | unset user.name

init . --> for create new local repos/project
add file.ext --> add file to track for changes or add to stage for commit
rm -r --cached filename| . -->for remove from track/stage 
show -->details of local repos
status -->show added files and not added files and modified in red & green.
commit -->opens editor| commit -m "mesage" -->its commit all staged files or added files.
commit --amend -m "replace with message" --> for only change previous commited message.
diff --> show's changes in txt if it is not commited only.
restore --> its restore changes in txt if it is not commited only.

show [hash-id] --> show's perticular commited info
branch ->show current branch |branch "new`branch" --> creates new branch|branch -d "new branch" -->its delete new branch
branch -a --> show's both local and repos branches.
branch -M "old branch"-->change to other branch | branch -r -->shows branch in repos;
remote add origin https://giturl.git --> to set repos path
push -u [remote namaspace][branchName] --> upload changes to repos.
*Note each branch is like a new repos in same repos.
pull --> to get files from repos;

Clone --> get copy of project to my local folder.
clone [git-url] --> it clones main branch
clone -b branch_name [git-url] --> it clones given branch name.

git rm -r --cached | git rm .git --> to remove local repos

REMOTE [defult remote name is origin]
git remote -v --> shows added remote url and namespace like 'origin'
git remote add [namesspace] [git-url]
git remote remove [namesspace] --> remove remote from this project.

BRANCH -->main/master is defult branch in git repos
branch checkout "newbranch" --> move to other branch 
branch checkout -      -->> move back to prev branch
1.branch "newbranch";
2.push -u origin newbranch; -->created and uploaded new branch. 
[OR] branch checkout -b "newbranch"; -- creates new branch and set this current one
3.before delete branch meve to other branch
4.git push origin -d remote_branch_name --> to delete remote branch.
