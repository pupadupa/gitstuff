
###difftool
`git difftool --tool=vimdiff --no-prompt`

###config and aliases
vim ~/.gitconfig
```
[user]
    email = user@example.com
    name = Name
[core]
    excludesfile = /Users/const/.gitignore
    editor = /usr/bin/vim
[alias]
  co = checkout
  ci = commit
  st = status
  br = branch
  hist = log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
  type = cat-file -t
  dump = cat-file -p
  d = difftool --tool=vimdiff --no-prompt


[diff]
    tool = vimdiff
[merge]
    tool = vimdiff
[core]
    editor = /usr/bin/vim
```
###git commands
forced pull:
```
git fetch --all
git reset --hard origin/master
```
