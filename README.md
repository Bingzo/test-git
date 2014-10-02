Practice of git operation
==================================
README.md abides [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) syntax.<br />
The guide of git operation can be found in [git-guid](http://rogerdudler.github.io/git-guide/).<br />
![alt text](http://github.com/github.png "github")
[SSH site: git@github.com:Bingzo/test-git.git](git@github.com:Bingzo/test-git.git)<br />
[HTTP site: https://github.com/Bingzo/test-git.git](https://github.com/Bingzo/test-git.git)<br />

### Generate a new SSH key
----------------------------------
    ssh-keygen -C 'zhouxxxxxxx@gmail.com' -t rsa 

### Create a new repository on the command line
----------------------------------
    touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:Bingzo/test-git.git
    git push -u origin master
### Some commands
----------------------------------
    git add -p

    git log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
    man git-log
    git log
    git log -p -2     # log recent two commits
    git log --stat
    git log --pretty=oneline
    git log --pretty=oneline --max-count=2
    git log --pretty=oneline --since='5 minutes ago'
    git log --pretty=oneline --until='5 minutes ago'
    git log --pretty=oneline --author=Bingzo
    git log --pretty=oneline --all
    git log --follow file.c
    git lot branch --not master

    git remote -v
    git status
    git commit --amend

    git push origin master ==> git push origin master:master # push [local]master to [remote]origin/master
    git push origin test:test
