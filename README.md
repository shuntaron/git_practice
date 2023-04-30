## create a new repository on the command line
```
echo "# git_practice" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:shuntaron/git_practice.git
git push -u origin main
```

## push an existing repository from the command line
```
git remote add origin git@github.com:shuntaron/git_practice.git
git branch -M main
git push -u origin main
```

## import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
```
[Import code](https://github.com/shuntaron/git_practice/import)
```
hoge
