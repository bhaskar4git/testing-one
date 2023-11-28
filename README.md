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
8. Check Git Branch status (Commited/Non commited files)  
    git status  
9. Create .gitignore file to exclude files and folders to commit in branch.  
10. Add files and folder to staging area for commiting  
        git add . (adds all the files/dir - mind gap between add and dot)  
        git add <file/folder> (Adds specific files/dir)  
11. Reset/Undo files/dir from staging area  
        git reset .  
        git reset <file/folder>  
12. Commit changes in branch  
        git commit - m "Text/Massege"  
13. Check Git Commit status  
        git log  
        (Shows each commits log with unique id)  
14. After making some more changes to files/folder to re-adding and re-commiting (all with single command)  
        git commit -a -m "Text Message"  
15. Now connect with remote git server like github, bitbucket, gitlab etc...(in this case we use github)   
16. Open github.com and login. Then create New Repository by defining name and discription. Then copy https git link of your repo.  
17. Check current git remote connection.  
        git remote  
        (Return nothing if no connection made available)  
18. Connect Local code to remote git server(github)  
        git remote add origin <repo link>  
19. Now check again remote connection  
        git remote (Show origin)  
        git remote -v (Show origin & URL)  
        git remote show origin (Show branches as well)  
20. Now upload/sync/push local branch(master) to remote repo(origin)  
        git push origin master -u  
21. Now this is new line. To test sync remote changes to local. For this:  
        First fetch remote branch  
        git fetch   
        Second merge remote fetched branch to local branch  
        git merge origin/master  
22. Another server to local sync method is pull(fetch + merge). It dosn't require fetch and merge run seperately.    
        git pull origin master  
        git pull (if we use -u flag with push)  
23. Cloning remote repository to local branch.  
        git clone <remote repo-url> <directory - optional>  
  
--------- Day 2 -----------  
  
24. Check/List branch  
        git branch  
25. Rename mastaer branch  
        git branch -M <new name>  
26. Create New branch  
        git branch <new branch name>  
27. Deleting branch  
        git branch -d <branch name>   
        (-d chack before deleting branch for any unsaved/un-commited/un-merged changes. Safe way)  
        git branch -D <branch name>  
        (-D Force delete. No checks perform.)  
28. Changing branch  
        git checkout <branch name>  
        git checkout - (Move to previous branch)  
29. Creating and changing branch  with single command  
        git checkout -b <branch name>  
30. Merging with local branch  
        git merge <branch name>  
31. Resolving conflicts while merging branch.  
        While merging branch if conflicts are it show options for  
                Accept Current Changes  
                Accept Incomming Changes  
                Accept Both Changes  
                Compare Changes  
        Check what conflicts are  
                git diff  
32. Abort Merging  
        git merge --abort  


