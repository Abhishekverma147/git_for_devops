Git Command Reference
1. Repository Setup
Create a new directory
mkdir git_for_devops

Navigate into the directory
cd git_for_devops/

Initialize a Git repository
git init

2. File Management
Create a new file
touch hello_mitro.txt

Create multiple files
touch Abhi.txt Destiny.txt

Remove a file
rm Abhi.txt

3. File Status
Check the current status of the repository
git status

View all files (including hidden)
ls -a

View detailed list of files
ls -lrt

4. Staging and Unstaging
Add a file to the staging area
git add Abhi.txt

Add multiple files to the staging area
git add abhi.txt Destiny.txt

Remove a file from the staging area
git rm --cached Abhi.txt

Unstage a file (restore to untracked)
git restore --staged abhi.txt

5. Commit Changes
Commit changes with a message
git commit -m "added new changes to abhi"

Commit with multiple files
git commit -m "adding abhi and Destiny changes"

6. Configuration
Set global Git username
git config --global user.name "Abhishekverma147"

Set global Git email
git config --global user.email "av230900@gmail.com"

7. View History
Show commit history
git log
8. Editing Files
Open a file in editor
vi abhi.txt

View file contents
cat abhi.txt

9. Cleanup and Reset
Clear the screen
clear

Restore a modified file
git restore abhi.txt
