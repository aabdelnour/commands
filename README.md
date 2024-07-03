# Linux Commands
ls <- List and variations (ls -a, ls -l)
pwd <- Present Working Directory
mkdir homework1 <- command to make a homework1 directory
rm -r homework1 <- Remove homework 1 directory (Needs -r on directories and no -r if its just one file)
cd homework1 <- Change directory to homework1 (May need to make it again if you deleted)
git init <- create a git repo
git status <-Git Status to check what is or is not tracked and what branch your on
vi .gitignore <- opens vi to edit a .gitignore file and add .sw to ignore swap files from vi
git add .gitignore
git commit -m "added swp files to ignore"
git checkout master
git merge updateReadme
ssh-keygen -t rsa -b 2048 <-Make ssh key and hit enter no passphrase
vi ~/.ssh/id_rsa.pub <-copy the contents of this to github > setting -> ssh keys -> add new key
Go on Github and create a repository for your homework1
git remote add origin git@github.com:kaw393939/is601homework1-spring2024.git <- replace the remote with the remote address for your own repo
git remote show <- Shows all remotes
git remote show origin <- Shows the details of the remote called "origin"
git push origin master <- Pushes to github
git checkout -b listInstructions <- creates a branch called listInstructions and checks it out for you
git checkout master <- Switches to master branch
git merge listInstructions <- merges listInstructions branch to the current branch (Check with git status and be on master)
history <- linux command to show history of commands
