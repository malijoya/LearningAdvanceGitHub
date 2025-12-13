Hi, I will add GitGitHub commands here Which I will use.

1. git --version => For knowing version 
2. git config --global user.name 'Muhammad Ali Joya' =>Tell who is Coder/Developer
3. git config --global user.email 'muhammadalijoya655@gmail.com' => Tells email of the Coder/Developer
4. git config --global init.defaultBranch main 
5. git status => Shows what updates we have done in project
6. git init => It initialize GitHub
7. git add . => It adds all the files to GitHub
8. git add readMe.md => add a single file, in this case it is readMe.md
9. git log => to show all the commits/log


Branching
1. git branch (branch-name) => add a new branch to the git
2. git checkout (branch-name) => switch to branch (branch-name)
3. if you want to go back to main then write: **git checkout main** => to go to main
4. Create a new branch and immediately move to it then write: **git checkout -b (branch-name)** => create and shift to that branch
5. git branch new-branch-name source-branch => to create a branch's branch. 

Commit
* git commit -m "message" => to commit message
Should write commit properly which should give answer to the question like why you commited like "Modified README.md"

git push --set-upstream origin (branch-name) => push from local to remote 
git pull => to make up-to-date your local branch with remote branch


Pull Request => Let you share your changes with team for review and feedback
* git pull

Merge Conflict
1. git branch dev-maj
2. git checkout -b dev-malijoya
3. git add .
4. git commit -m "Modify Readme by changing last lines"
5. git push -u origin dev-malijoya
6. 
