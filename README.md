# maven then git

The first steo is to create a maven fie 

Then test it to see if it runs 
java -cp target/ccc-1.0-SNAPSHOT.jar john.org.App

## Initilise a git repository
git init


## set up git vatabless
- git config --list
- git config --global user.email "john@john.org"
- git config --global user.name  "John"
- git config --global alias.co checkout
- git config --global alias.ci commit
- git config --global alias.st status
- git config --global alias.br branch
- git config --global alias.lg 'log –pretty=oneline'
- git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph –date=short"
- git config --global core.editor nvim
- git config –list



## Add Linux aliases 
- alias s='clear;echo "git status";git status '
- alias a='git add '
- alias aa='git   add -A '

- alias ra="git rm --cached '*'"
- alias r="git rm --cached "
- alias rh='clear;echo "git reset HEAD -- ";git reset HEAD -- '
- alias r='clear;echo "git reset";git reset '

- alias l='clear ; echo "git log ";git log -1'
- alias ll='clear ; echo "git log ";git log -2'
- alias la='clear ; echo "git log All";git log'
- alias lk='clear;git log "--pretty=format:\"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue\\ [%cn]\""'

- alias d="clear&&printf 'git Diff \n\n'&&git diff
- alias d='git diff'



