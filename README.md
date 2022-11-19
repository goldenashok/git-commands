![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
# git-commands
# Basic Git Commands

1. npm help
   - npm help  -> Long hand
   - npm -> shorthand

| Long Hand | Short Hand | Usage |
| --- | --- | --- |
| npm help | npm | Get Help |
| npm init --yes | npm init y| Default package.json |
| npm version | npm -v | check npm version |
| npm uninstall package-name | npm un package-name | uninstall a package |
| npm update package-name | npm up package-name | update a package |
| npm install --save-deve package-name | npm i -D package-name| install a package as a dev dependency |
| npm install --global package-name | npm i -g package-name | install a package globally |
| npm install package-name | npm i package-name | install a package |
| --- | --- | --- |


1. ```git rm --cached <file name>```
   - Discard file changes
2. ```git restore <file name>```
   - Discard file changes
3. ```git log```
4. ```git log --oneline```
5. ```git reset --soft <committed version no>```
6. ```git reset --hard <committed version no>```
7. ```git revert <committed version no>```
8. ```git revert <committed version no> --no-commit```
9. ```git checkout -b <branch name>```
   - create new branch and switch to the created branch
10. ```git checkout <branch name>```
11. ```git merge <old branch name> <new branch name>```
12. ```git branch -d <branch name>```
13. ```git rebase``` vs ```git cherry-pick``` vs ```git stash```
      | git rebase | git cherry-pick | git stash |
      | --- | ---|---|
      |commands : ```git rebase``` | ```git cherry-pic <committed version no>``` | ```git stash```|
      |---|---|---|---|
   
14. Squash
      - command : ```git rebase -i HEAD~[<commit no, example 1>]```
      - or
      - command : ```git rebase -i <commit id>```
 15. ```git status```
      - show the modified files
 16. ```git add <file path>```
      - add files to staged area from unstaged
 17. ```git commit -m "Mesage"```
      - Add message to Commit
 18. ```git push```
      - ush commit to remote url (github or similar)
 19. ```git stash pop```
      - git stash pop = git stash apply + git stash drop
 20. ```git pull```
      - git pull updates new changes from the remote (update local changes with with remote changs)
 21. ```git commit --amend```
      - Edit commit message (only for the latest/last commit)
 22. ```git commit -am "commit message"```
 
       ```git commit -am``` used ommit the ```git add``` command when committing
       
      ##vExample
      ```sh
      git add.
      git commit -m "Commit message"
        instead of
      git commit -am "Commit message"
      ```
     
