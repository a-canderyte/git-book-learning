# Git

```
git status
```

```
git add
```

```
git commit -m "Message"
```

```
git log
```

```
git checkout 4125
```

go back in time with 4 digits / characters of your head commit

```
git checkout main/master
```

go back to the most recent commit, navigate to master/main branch

```
git branch name-of-new-branch
```

```
git merge master/main
```

merge / pull master features into your branch

you need to be in your destination branch

```
git diff master
```

check what is different

```
git remote add origin https://github.com/a-canderyte/DevOps_Monday_Existing.git
```

add github.com repo to local

```
git push -u origin main
```

push your local repo to github public repo

```
git pull
```

to take the changes from remote repository

```
git clone https://linkfromremoterepo.com
```

make sure it is in a different directory so that it doesnt have another repo

also make sure to move to the repo's directory name/title

```
git checkout -b <branchname>
```

to create new branch and move to that branch in one go

```
git rebase
```

moving the main branch ahead with the feature branch

```
^
```

moving upwards once commit at a time

```
~<num>
```

moving upwards a number of times

```
git branch -f main HEAD~3
```

moves by force the main branch to three parents behind HEAD

```
git reset
```

reverses changes by moving a branch reference backwards in time to an older commit. It will move a branch backwards as if the commit had never been made in the first place.

```
ex: git reset HEAD~1
```

```
git revert
```

in order to reverse changes and share those reversed changes with others, we need to use git revert

```
ex: git revert HEAD
```

```
git cherry-pick <Commit1> <Commit2> <...>
```

straightforward way of saying that you would like to copy a series of commits below your current location (HEAD)&#x20;

```
git rebase -i
```

<figure><img src=".gitbook/assets/Screenshot 2022-09-08 at 12.15.32.png" alt=""><figcaption></figcaption></figure>

```
git tag v1 C1
```

<figure><img src=".gitbook/assets/Screenshot 2022-09-08 at 12.23.04.png" alt=""><figcaption></figcaption></figure>

```
git describe
```

<figure><img src=".gitbook/assets/Screenshot 2022-09-08 at 12.27.08.png" alt=""><figcaption></figcaption></figure>

