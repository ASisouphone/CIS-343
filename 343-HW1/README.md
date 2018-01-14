<h1>Git Commands</h1>

git
- Show the Git help menu containing all the Git commands

git init
- Initializes a Git repository in the current directory

git status
- Shows the current state of the project which includes currently staged, unstaged, and untracked files

git add < Filename >
- Adds the file to the staging area in order to track it

git commit -m “Message”
- Records changes to the respository and shows a message on the commit

git log
- Shows all the changes committed so far

git remote add < Remote Name > < Repository URL >
- Adds a remote repository to push or pull to

git push -u < Remote Name > master
- Will add files onto Github
- -u Tells git to remember the parameters
- master is the default local branch name

git pull < Remote Name > master
- Will get the current files on the Github repository along with their changes

git diff HEAD
- Find differences in the most recent commit

git diff --staged
- See changes that were just staged

git reset < Filename >
- Removes file from stage

git checkout -- < Target >
- Gets rid of all the changes since the last commit to the target

git branch < Branch Name >
- Creates another branch apart from master
- -d before branch to delete

git rm < Filename >
- Deletes files and stages those files to be deleted on Github

git merge < Branch >
- Merge specified branch with current branch
