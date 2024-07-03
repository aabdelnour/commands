# Linux Commands
1.  ls <- List and variations (ls -a, ls -l)
2.  pwd <- Present Working Directory
3.  mkdir homework1 <- command to make a homework1 directory
4.  rm -r homework1 <- Remove homework 1 directory (Needs -r on directories and no -r if its just one file)
5.  cd homework1 <- Change directory to homework1 (May need to make it again if you deleted)
6.  git init <- create a git repo
7.  git status <-Git Status to check what is or is not tracked and what branch your on
8.  vi .gitignore <- opens vi to edit a .gitignore file and add *.sw* to ignore swap files from vi
9.  git add .gitignore
10. git commit -m "added swp files to ignore"
11. git checkout master
12. git merge updateReadme
13. ssh-keygen -t rsa -b 2048  <-Make ssh key and hit enter no passphrase
14. vi ~/.ssh/id_rsa.pub <-copy the contents of this to github > setting -> ssh keys -> add new key
15. Go on Github and create a repository for your homework1 
16. git remote add origin git@github.com:kaw393939/is601homework1-spring2024.git <- replace the remote with the remote address for your own repo
17. git remote show <- Shows all remotes
18. git remote show origin <- Shows the details of the remote called "origin"
19. git push origin master <- Pushes to github 
20. git checkout -b listInstructions <- creates a branch called listInstructions and checks it out for you
21. git checkout master <- Switches to master branch
22. git merge listInstructions <- merges listInstructions branch to the current branch (Check with git status and be on master)
23. history <- linux command to show history of commands
