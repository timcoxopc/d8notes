## Git

### Reset to Origin
```bash
git fetch origin
git reset --hard origin/master
```

### Git Clone
```bash
git clone https://github.com/timcoxopc/govcms8_uikit_starter_subtheme
```

### Commiting and Pushing
```bash
git add .
(git status) - to check staged files
git commit -m 'commit message'
git push origin branchname
```

### Branches
Create the branch on your local machine and switch in this branch :
```bash
$ git checkout -b branch
```

### Change working branch
```bash
$ git checkout branch
```

### Push the branch 
```bash
$ git push origin branch
```

### Setting up new repos
If using github need to set up repo there first
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin url
git remote -v
git push origin master
```
