# Learn Git

## Basic git commends

1.git init

2.git add

3.git commit -m "xxx"

4.git status

5.git diff

6.git log     git log --pretty=oneline   git log --graph --pretty=oneline --abbrev-commit

7.git reset --hard HEAD^(HEAD^^, HEAD-100)       git reset --hard 1094a(commit id)

8.git reflog

9.feature:Git tracks changes.

10.git checkout -- filename

11.git reset HEAD filename

12.rm filename

13.git rm filename (similar to git add)

14.github related: ssh-keygen -t rsa -C "youremail@example.com"

copy id_rsa.pub into github ssh settings

then ssh -T git@github.com to check whether the connection is ok



git remote add origin git@github.com:username/learngit.git

git push -u origin master (for the first time)

git push origin master

git clone ssh/http

15.git checkout -b dev (git branch dev  git checkout dev)   git switch -c dev  (git switch master)

git branch

git merge dev (merge dev branch to the branch now)     git merge --no-ff -m "merge with no-ff" dev 

git branch -d dev

16.git stash

git stash list 

git stash apply   git stash drop    git stash apply stash @{0}

git stash pop (deleting stash documents)

17.git cherry-pick commit_id

18.git branch -D <name>

19.git remote

git remote  -v

20.git checkout -b branch-name origin/branch-name

21.git rebase

22.git tag <name>

git tag

git tag <name> commit_id

git show <tagname>

git tag -a <tagname> -m <description>

git tag -d <tagname>

git push origin <tagname>

git push origin --tags





























