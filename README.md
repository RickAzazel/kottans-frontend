# kottans-frontend

Introduction to Git and GitHub

<!--- 1st week --->
git diff -u - used to compare two files, line by line, and have the differing lines compared side-by-side in the same output. 
git patch - used for applying file differences.

<!--- 2nd week --->
git commit -a - stages files automatically.
git log -p - produces patch text.
git show - shows various objects.
git diff --staged - an alias to --cached, this will show all staged files compared to the named commit.
git add -p - allows a user to interactively review patches to add to the current commit.
git mv - moves a file.
git rm - deletes, or removes a file.

.gitignore files are used to tell the git tool to intentionally ignore some files in a given Git repository.

git checkout - used to switch branches.
git reset - resets the repo, throwing away some changes. 
git commit --amend - used to make changes to commits after-the-fact, which can be useful for making notes about a given commit.
git revert - makes a new commit which effectively rolls back a previous commit.

rollback commits in Git - https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things

git branch - used to manage branches.
git branch <name> - creates the branch.
git branch -d <name> - deletes the branch.
git branch -D <name> - forcibly deletes the branch.
git checkout <branch> - switches to a branch.
git checkout -b <branch> - creates a new branch and switches to it.
git merge <branch> - merge joins branches together. 
git merge --abort - if there are merge conflicts (meaning files are incompatible), --abort can be used to abort the merge action.
git log --graph --oneline - this shows a summarized view of the commit history for a repo.
  
  
  
  
  
  
  
  
  
  
  
  
  
  
