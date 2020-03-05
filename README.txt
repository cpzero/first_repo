Git is a version control system that stores snapshots of your code.
It creates a linear timeline that allows you to go back in time to review or reuse code.
There are 3 sections to git:
    a. Working directory - files to be tracked are moved to
    b. Staging Area - files are held here until they are committed to the Git Repository
    c. Git Repository - Where all our snapshots are stored

Here are the git commands that you need to know:
1. Inside the project folder initialize an empty Git Repository type 'git init' and press enter
2. cd to the project folder then Create files for the project type 'touch filename.ext' and press enter
3. Inside the project folder type 'dir' to see the newly added file(s)
4. Inside the project folder type 'git status' and press enter - files shown in RED are NOT TRACKED
5. To add files to the Staging Area type 'git add filename.ext' - no messages so...
6. type 'git status' and press enter. files added to the staging area will show up GREEN
7. To commit the file in the Staging Area to Git Repository type 'git commit -m "Add filename.ext"'
8. To view the history of commits (snapshots) type 'git log'

How to add multiple files with the same file extension that are in the Working Directory to the Staging Area
1. Use the wildcard command type 'git add *.ext' then press enter
2. type 'git status' and press enter to show the .ext files newly added to the Staging Area
3. To commit all the files in the Staging Area to the Git Repository type 'git commit -m "Add all files with .ext"'

How to add all files in the Working Directory (inc hidden file) to the Staging Area and the commit to Git Repository
1. type 'git add -A' and press enter
2. To check all file are in the Staging Area type 'git status' press enter
3. To commit all the files in the Staging Area type 'git commit -m "Add all files"' press enter
4. To check status of the files type 'git status' and press enter
5. To show the snapshots type 'git log' press enter

How to remove files from the Staging Areas
1. type 'git reset HEAD filename.ext' press enter or
2. type 'git restore --staged filename.ext' press enter
2. type 'git status' to see the file has been removed from the Staging Area and is no longer tracked

How to commit files held in the staging area to the Git repository
1. type git commit -m "Add <filename.ext>"

How to ignore files and folders:
1.

This is a .txt file type and we'er going to add it to git's stage