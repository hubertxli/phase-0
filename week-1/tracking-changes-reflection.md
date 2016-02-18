How does tracking and adding changes make developers' lives easier?
If multiple developers are working on the same project, its important to be able to turn back time if someone makes a mistake or decides to take a different approach.

What is a commit?
A commit a command that saves a directory a a point in time it can be accessed at any time.

What are the best practices for commit messages?
Commit messages should sound like commands.

What does the HEAD^ argument mean?
HEAD^ is the commit before the current commit.

What are the 3 stages of a git change and how do you move a file from one stage to the other?
untracted, changes to be committed and committed. Use "git add [file name]" to go from the first to the second stage. "git commit" to go from the second to the third.

Write a handy cheatsheet of the commands you need to commit your changes.
git add [file name] -- set up file or directory for commit 
git commit -- to commit
git reset HEAD -- to undo commit 

What is a pull request and how do you create and merge one?
A pull requests takes a repository and copies it into another as a branch to be merged.
the command is "git pull [outside repository] [repository you want to change]"
pull = fetch + merge

Why are pull requests preferred when working with teams?
pull requests allow multiple team members to work seperately and combine their work at a later time.