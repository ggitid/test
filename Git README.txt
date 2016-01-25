To copy down the commits from a repository
git clone @respository
Eg: git clone https://github.com/udacity/asteroids.git
Note: Remember to "cd" the folder first

To find the list of commit history (oldest is at the bottom, Press "Q" to exit log)
git log 

To find the difference of commit
git diff @Id1 (better put older here as Id1) @Id2 (more recent as id2)

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

****************************************
Use notepad++ as the commit message core editor
the code in git bash is:
git config --global core.editor "D:\Notepad++\notepad++.exe"
****************************************