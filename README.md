Practice of git operation
==================================
### --Bingzo
![github](https://github.global.ssl.fastly.net/images/modules/open_graph/github-logo.png)[image]: http://github.com/github.png "github"
----------------------------------
    [SSH site: git@github.com:Bingzo/test-git.git](git@github.com:Bingzo/test-git.git)<br />
    [HTTP site: https://github.com/Bingzo/test-git.git](https://github.com/Bingzo/test-git.git)<br />
----------------------------------

### Generate a new SSH key
    ssh-keygen -C 'zhouxxxxxxx@gmail.com' -t rsa 

### Create a new repository on the command line
    touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:Bingzo/test-git.git
    git push -u origin master
### Some commands
    git log
    git log -p -2
    git log --stat
    git remote -v
    git status
    git commit --amend
