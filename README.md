#This is a practice of git operation.
#
#SSH:git@github.com:Bingzo/test-git.git
#HTTP:https://github.com/Bingzo/test-git.git
#
#--Bingzo
#

#Generate a new SSH key
    ssh-keygen -C 'zhouxxxxxxx@gmail.com' -t rsa 

#Create a new repository on the command line
    touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:Bingzo/test-git.git
    git push -u origin master
