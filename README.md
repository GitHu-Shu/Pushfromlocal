# This is my second day and I have learned following things

- How to install Git 
- How to install VS Code (Visual Studio Code)
- Sign Up on GitHub web application for version control system
- to Post installing Git Bash how to check version
        - here is command that is need to check which version of git is installed on Local
        - Git --version (To check version of git installed on Local)
        
- How to Clone project/repository on to local from remote
        - First Config the VS Code with GitGub through following Commands
        - Git config --global user.name "Username" #User name which is given at GitHub
        - Git config --global user.email "Someone@email.com" # Email that account created on github
        - Git config --list # To check credential is setup 
        - Git clone < Enter link > # you can find this on Github>My_profile>Repositary>Code>HTTP(Clone using the web URL.) #Clone used for clone repository on local machine
        
- How to check status post closing
        - Git Status command is used to check status of the code
        - Lets Creat one file under directory/folder 
        - Post creat a README.md and writing introduction of ptoject in this file
        -Initially if we checked the status 

- Push Local Repository to Remote(GitHub)
        - First need to initate the Local repo
        - Enter git init # will initate and make this dir/Repo as Git reposiatory (Initialized empty Git repository in E:/Git Demo/Newmkdir/.git/)
        - Initiatlly this Repo and file within local having untracked file
        - Enter git status to check status of the file under repo
        - nothing added to commit but untracked files present (use "git add" to track)
        - Git add . to add all untrack/modify file at one go
        - Post Enter file get Added >> now need to commit this file
        - Git commit -m "Updated message should give" # this wil allow to commit all the untracked/modify post adding it
        - Create New repo on Github >> without readme.md file>> creat repo>> Quick setup>> Copy link
        - Git remote add origin < link >
        - git remote -v (check origin at remote/ to verify remote)
origin  https://github.com/GitHu-Shu/Pushfromlocal.git (fetch)
origin  https://github.com/GitHu-Shu/Pushfromlocal.git (push)
        - Git Branch *master branch is visible rename it 
        - git branch -M main (changed master branch name to main)
        - git push -u origin main (To push code on remote repo created )
        - Refresh repo on Github

- How to add Branches
        - Git checkout -b "branch name" (to create branch)
        - Git branch (to check branchs)
        - Git checkout -d "exsiting branch name" (to delete)
        -