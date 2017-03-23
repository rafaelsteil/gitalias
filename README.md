# gitalias
The Git aliases I use

# Command list
```ini
[color]
  ui = auto
[color "branch"]
  current = yellow reverse
  local = yellow
  remote = green
[color "diff"]
  meta = yellow bold
  frag = magenta bold
  old = red bold
  new = green bold
[color "status"]
  added = yellow
  changed = green
  untracked = cyan
[push]
  default = simple
[rerere]
  enabled = true
[alias]
  s = status
  co = checkout
  d = diff
  cm = commit -m
  ca = commit -am
  p = push origin
  pf = push --force origin
  pr = pull --rebase origin
  ls = log --pretty=format:"%C(yellow)%h%Cred%d %Creset%s%Cgreen [%cn]" --decorate --graph
  rh = reset --hard
  # Log showing changed files
  ll = log --pretty=format:"%C(yellow)%h%Cred%d %Creset%s%Cgreen [%cn]" --decorate --numstat
  # Reset file
  fl = log -u 
[credential]
  helper = wincred
[stash]
  showPatch = true
```

# References
- http://durdn.com/blog/2012/11/22/must-have-git-aliases-advanced-examples/
- https://github.com/GitAlias/gitalias
