# kottans-frontend

<h3>Introduction to Git and GitHub</h3>

<p>#1st week</p>

```
$ git diff -u 
Used to compare two files, line by line, and have the differing lines compared side-by-side in the same output. 
```
```
git patch
Used for applying file differences.
```

<p>#2nd week</p>

```
git commit -a 
Stages files automatically.
```
```
git log -p  
Produces patch text.
```
```
git show 
Shows various objects.
```
```
git diff --staged 
An alias to --cached, this will show all staged files compared to the named commit.
```
```
git add -p 
Allows a user to interactively review patches to add to the current commit.
```
```
git mv 
Moves a file.
```
```
git rm 
Deletes, or removes a file.
```

.gitignore files are used to tell the git tool to intentionally ignore some files in a given Git repository.

```
git checkout 
Used to switch branches.
```
```
git reset 
Resets the repo, throwing away some changes. 
```
```
git commit --amend 
Used to make changes to commits after-the-fact, which can be useful for making notes about a given commit.
```
```
git revert 
Makes a new commit which effectively rolls back a previous commit.
```

rollback commits in Git - https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things

```
git branch 
Used to manage branches.
```
```
git branch <name> 
Creates the branch.
```
```
git branch -d <name> 
Deletes the branch.
```
```
git branch -D <name> 
Forcibly deletes the branch.
```
```
git checkout <branch> 
Switches to a branch.
```
```
git checkout -b <branch> 
Creates a new branch and switches to it.
```
```
git merge <branch> 
Merge joins branches together. 
```
```
git merge --abort 
If there are merge conflicts (meaning files are incompatible), --abort can be used to abort the merge action.
```
```
git log --graph --oneline 
This shows a summarized view of the commit history for a repo.
```

<h3>Linux, Command Line, HTTP Tools</h3>

<h5>Linux Survival</h5>

```
cd 
Change to another directory.
```
```
mv 
Move files and directories. Rename files and directories.
```
```
ls 
List the contents of a directory.
```
```
pwd 
Print your current working directory.
```
```
mkdir 
Make a new directory.
```
```
more 
Display the contents of a file.
```
```
cp 
Copy files.
```
```
rm Remove files.
```
```
group 
List the groups you are in.
```
```
rmdir 
Remove empty directories.
```
```
chmod 
Change file permissions.
```
```
cat 
Concatenate files.
```
```
man 
View manual pages.
```
```
find 
Locate files.
```
```
finger 
Show user information.
```
```
df 
Command shows free disk space
```
```
ps 
Command shows process status 
aux 
Option to the above command shows all system processes.
```
```
kill 
Command tells a process to die gracefully.
-9 
Option to the above command tells a process to die immediately.
```
```
grep 
Command finds words in text.
```

| - symbol sends output to another program.

-r - 'cp' and 'rm' option acts on trees.
