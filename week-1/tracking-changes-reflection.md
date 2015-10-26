How does tracking and adding changes make developers' lives easier?
Tracking allows for the files to be updated and back up at the same time. Any changes you make will be visible in the future for examination.

What is a commit?
A commit is a command that allows you to make changes to the repository.

What are the best practices for commit messages?
Written in the imperative, capitalized, short (50 chars or less), summarize actions taken

What does the HEAD^ argument mean?
HEAD^ means the first parent of the tip of the current branch.

What are the 3 stages of a git change and how do you move a file from one stage to the other?
git add, git commit, git push. you add the changes you want, then commit them with a message, then push them to your git repository. git status lets you know what is happening.

Write a handy cheatsheet of the commands you need to commit your changes?
master
git pull
git checkout -b branch-name
work work work
git add
git commit -m "COMMIT MESSAGE"
git push origin branch-name
git checkout master
git fetch origin master
git merge origin/master

What is a pull request and how do you create and merge one?
Pull requests let you tell others about changes you've pushed to a repository on GitHub. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.
Create a branch to work on using "git checkout -b new-branch", create a change using "subl .", check "git status", add change using "git add", commit change using "git commit", and push request using "git push". Then go to the github tab and click "create pull request" and click "merge".

Why are pull requests preferred when working with teams?
Teams can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

Go through the git workflow you just established and add your reflection to the file. (If you are creating a video