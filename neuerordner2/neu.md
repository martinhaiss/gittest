# How To Branch
## step by step
- create a new branch: `git ceckout -b <name of your new branch>`
- type `git add .`
- open Visual Studio Code `code .`
- work on the branch with Visual Studio Code
- don't forget to save! `cmd + s`
- after work is done don't forget to `git add .`
- time to commit: ` git commit -m"<comment here>` 
- time to push: `git push --set-upstream origin <name of your branch>`
 
*you can always check your status with `git status`*

- Go to [github.com](https://www.github.com)
- pull request
- ask your fellow collegues for a review
- make changes if necessary
- merge branch to main (solve conflicts before if necessary)


### last but not least
- switch from branch to main: `git checkout main`
- don't forget to pull: `git pull`
- now you can delete your branch if you want: `git branch -d <name of your branch>`