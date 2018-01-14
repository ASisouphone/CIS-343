<h1>Git Commands</h1>

<b>git</b>
- Show the Git help menu containing all the Git commands

<b>git init</b>
- Initializes a Git repository in the current directory

<b>git status</b>
- Shows the current state of the project which includes currently staged, unstaged, and untracked files

<b>git add < Filename ></b>
- Adds the file to the staging area in order to track it

<b>git commit -m “Message”</b>
- Records changes to the respository and shows a message on the commit

<b>git log</b>
- Shows all the changes committed so far

<b>git remote add < Remote Name > < Repository URL ></b>
- Adds a remote repository to push or pull to

<b>git push -u < Remote Name > master</b>
- Will add files onto Github
- -u Tells git to remember the parameters
- master is the default local branch name

<b>git pull < Remote Name > master</b>
- Will get the current files on the Github repository along with their changes

<b>git diff HEAD</b>
- Find differences in the most recent commit

<b>git diff --staged</b>
- See changes that were just staged

<b>git reset < Filename ></b>
- Removes file from stage

<b>git checkout -- < Target ></b>
- Gets rid of all the changes since the last commit to the target

<b>git branch < Branch Name ></b>
- Creates another branch apart from master
- -d before branch to delete

<b>git rm < Filename ></b>
- Deletes files and stages those files to be deleted on Github

<b>git merge < Branch ></b>
- Merge specified branch with current branch
