# Description
Store manifest to quickly download github external repo using git-repo

# Installing repo
```
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.local/bin/repo
chmod a+x ~/.local/bin/repo
```

# Setup the worktree
```
mkdir <dir> && cd <dir>
```
## ssh repo
```
repo init -u ssh://git@github.com/Mizux/third-party.git
```
## https repo
```
repo init -u https://github.com/mizux/third-party.git
```

# Update the worktree
```
repo sync -j8
```

Now all is done ...
