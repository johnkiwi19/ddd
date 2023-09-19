# maven then git

The first steo is to create a maven fie 

Then test it to see if it runs 
java -cp target/ccc-1.0-SNAPSHOT.jar john.org.App

## Initilise a git repository
git init


## set up varables
- git config --list
- git config --global user.email "john@john.org"
- git config --global user.name  "John"
-  git config --global alias.co checkout
- git config --global alias.ci commit
- git config --global alias.st status
- git config --global alias.br branch
- git config --global alias.lg 'log –pretty=oneline'
- git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph –date=short"

## git config –list

