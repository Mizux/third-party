# Description
Store manifest to quickly download github external repo using git-repo

# Installing repo
```
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.local/bin/repo
chmod a+x ~/.local/bin/repo
```

# Create the worktree
```
	mkdir <dir> && cd <dir>
	repo init -u https://github.com/mizux/third-party.git
	repo sync -j8
	cd ..
```

Now all is done ...
