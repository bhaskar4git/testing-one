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
15. Now connect with remote git server like github, bitbucket, gitlab etc...(in this case we use github)                                         
16. Open github.com and login. Then create New Repository by defining name and discription. Then copy https .it link of your repo.
17. Check current git remote connection.
        git remote
        (Return nothing if no connection made available)
18. Connect Local code to remote git server(github) 
        git remote add origin <repo link>
19. Now check again remote connection
        git connect (Show origin)
        git remote -v (Show origin & URL)
        git connect show origin (Show branches as well)
20. Now upload/sync/push local branch(master) to remote repo(origin)
        git push origin master -u        