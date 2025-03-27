# Git Workflow and Commands

## Helpful Links
- [W3 Schools Git Tutorial](https://www.w3schools.com/git/git_getstarted.asp?remote=github)
- [Git Workflow Visualization](https://ndpsoftware.com/git-cheatsheet.html#loc=local_repo)

## Commands

```bash
git log

git config --global user.name "username"

git config --global user.email "your@email.com"

git config --global init.defaultBranch main

git init
    (Command will produce a .git directory which contains metadata GIT created to track changes to files and folders within that directory. 
    GIT now knows that it should track the directory you initialized it on, treating it as a local GIT repository.)

git status

git add FILENAME

git commit -m "<your commit message>"

git remote -v

git remote add NAME URL
    (NAME typically is called 'origin')
    (Make sure to use SSH URL, not the HTTPS one)

git push -u REMOTENAME main

```

## GIT SFPT Methods
- Deploybot
- Codeship
- Beanstalk

## Deploy from GitHub
- [Deploy WordPress to WP Engine](https://github.com/marketplace/actions/deploy-wordpress-to-wp-engine)
- [GitHub Action General Info](https://app.getguru.com/card/idEMMXXT/Github-Action-General-Info)

