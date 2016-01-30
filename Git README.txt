Working Directory >> Staging Area >> Repository


To copy down the commits from a repository
git clone @respository
Eg: git clone https://github.com/udacity/asteroids.git
Note: Remember to "cd" the folder first

To find the list of commit history (oldest is at the bottom, Press "Q" to exit log)
git log
git log --graph --oneline master coins

To find the difference of commits
git diff @Id1 (better put older here as Id1) @Id2 (more recent as id2)

To find the difference between staging & working
git diff [Without Ids]

To find the difference between staging & repository
git diff --staged

To find the difference between this commit & its parent
git show @Id

To set to the particular commit ID
git checkout @Id

To reset to the initial commit ID (which is also your oldest commit)
git checkout master

To set the difference color
git config --global color.ui auto

Examples of Commit IDs
f19cb1b80fe27e938e4d72770ca0a42f25e99ecc b0678b161fcf74467ed3a63110557e3d6229cfa6

To restore to that particular point of time/commit
git checkout @id1
Note: the most recent git log will display that id, so remember to jot it down


****************************************
Inserted 3 files into User~User Directory
.bash_profile
git-completion.bash
git-prompt.sh
****************************************


To create new repository
git init

To view git status
git status

To add files into staging area before subsequently into commit
git add @file

To reset a added file in the staging area
git reset @file

To reset changes made in the working directory & staging area
git reset --hard
****************************************
Use notepad++ as the commit message core editor
the code in git bash is:
git config --global core.editor "D:\Notepad++\notepad++.exe"
****************************************

To create branches of different paths of your projects
git branch : to see what branch are you on (default: master)
git branch @new_name : to create a new branch
git checkout @new_name : to switch to another branch
git checkout -b @new_name : checkout & create new branch at the same time
git branch -d @new_name : delete that branch
git merge --abort : exit merging process
