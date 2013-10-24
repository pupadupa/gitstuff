gitstuff
========

#aliases
vim ~/.bash_profile
http://githowto.com/aliases

alias gs='git status '
alias ga='git add '
alias gc='git commit'
alias gd='git diff'
alias go='git checkout '

alias got='git '
alias get='git '
alias gi='git '


#Usefull stuff
##difftool
git difftool --tool=vimdiff --no-prompt

vim ~/.gitconfig
[diff]
    tool = vimdiff
[merge]
    tool = vimdiff
