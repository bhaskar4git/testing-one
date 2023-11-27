#This is first git test.

Lets start some git learning.

Topic Completed:

1. Understanding Git
2. Installing Git/Git Bash (Windows & Linux)
3. Check installed Git Version 
    git --version
4. Installing VS Code
5. Set Git config using
    git config user.name
    git config user.email
    git config core.editor
6. Check Git Config
    git config --list
7. Initiate Git
    git init  
8. Check Git Repo status (Commited/Non commited files)
    git status
9. Create .gitignore file to exclude files and folders to commit in repo.
10. Add files and folder to staging area for commiting
        git add . (adds all the files/dir - mind gap between add and dot)
        git add <file/folder> (Adds specific files/dir)
11. Reset/Undo files/dir from staging area
        git reset .
        git reset <file/folder> 
12. Commit changes in repo
        git commit - m "Text/Massege" 
13. Check Git Commit status
        git log
        (Shows each commits log with unique id)
14. After making some more changes to files/folder to readding and re commiting(all with single command)
        git commit -a -m "Text Message"                                
