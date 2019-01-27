
# GitHub
## About GitHub : 
GitHub is a **distributed** Version control system ( also known as Source code management) used for tracking changes to the file(s).
* GitHub provides a platform for multiple developers to work simultaneously.
* GitHub adds flexibility to developers to keep track of file changes locally during offline and can later push changes to server when required.
* GitHub is heavily used for open source projects.

### Version Control System(VCS) :
There are 2 types of VCS 1) Centralized VCS and 2) Distributed VCS
1) Centralized VCS : It works on a client-server mechanism. Client will be downloading only a single set of files from a remote repository to a local repository.

Examples: Concurrent VCS(CVS), SubVersion(SVN)

2) Distributed VCS : Each client acts as a separate VCS. Client will get the full history of files in the repository downloaded in the system.
It is time efficient compared to Centralized VCS. Only push and pop requests are handled by the server. Other all git commands are handled by the local repository allowing user to track files in offline mode.

Examples: GitHub, Mercurial, Bazaar

### Operations done on GitHub:
* Create a repository on GitHub and copy the clone link.
* Get the local copy of the remote repository on the client machine.

`git clone remote_repository_clone_link`

* Steps for adding new file to the remote repository 

`git add file_name` ( --> Adds the new file to the staging area )

`git commit` ( --> Checks for files in staging area, and modified files. If present commit the files to the local repository) 

`git push` ( --> All files in the commit history are pushed to the remote repository on the server )

* Steps for creating a branch

clone the repository to the local system from server and execute

`git branch` ( --> to get list of all branches for the cloned repository )  

`git branch branch_name` ( --> to create a new branch and also changes the current local repository to the branch)

(or) `git checkout -b branch_name`

* Steps for creating a tag

clone the repository to the local system from server and execute

`git tag tag_name`

* Steps to update the local repository

`git pull`

1. Downloaded GitHub desktop application from https://desktop.github.com/
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/GitHub1.png)

2. Created online GitHub account and configured Desktop GitHub after installation
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/GitHub2.png)

# GitShell
## About GitShell : 
Git Bash is comprised of two parts i.e, Git and Bash. Git is a version control system and Bash is a unix shell command line interface for windows.

1. Downloaded GitShell from https://git-scm.com/downloads
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Screenshot%20(36).png)

2. Uploaded new files to github repository using GitShell 
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Screenshot%20(37).png)

# ZenHub
## About ZenHub : 
ZenHub is a browser extension that automatically adds features into GitHub interface. ZenHub provides task boards, burndown charts, milestones and to-do lists. 
* Task boards are used for managing issues.
* Burndown charts and milestones are used to track speed of sprints.

1. Added ZenHub plugin to GitHub
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/ZenHub2.png)
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/ZenHub5.png)

# Creatly Account
## About Creately : 
Creately is a online diagramming tool which is mainly used for drawing Unified Modeling Language(UML) diagrams. It is also used for drawing flowcharts, network diagrams, venn diagrams e.t.c

1.Go to https://creately.com/ and Sign-up for new account 
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Creatly0.png)
2. After Sign-up, account will be created
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Creatly2.png)

# Web storm
## About Web storm : 
Web storm is a modern Java Script IDE with coding assistance. 
* Its features include refractoring, auto code completion, and error detection for different languages like HTML, CSS, Node.js, and JS. 
* WebStorm can automatically add imports from the symbols defined in the project and as well as its dependencies.

1. Downloaded Web storm from https://www.jetbrains.com/webstorm/
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Webstorm1.png)
2. After completion of installation following window will be opened
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Webstorm6.png) 

# Brackets
## About Brackets : 
Brackets is a light weight source code editor developed by Adobe. It is primarily designed for front-end developing and web designing like HTML, CSS, JS, Ruby, Python and PHP.
* Unlike Atom and Sublime, Brackets is fast and space effective.
* Brackets provides quick editing and line preview which makes front-end work much easier.

1. Downloaded Brackets from http://brackets.io/
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Brackets1.png)

2.After completion of installation, Brackets work space will be opened
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Brackets3.png)

3. Added AngularJS and Ionic extensions to Brackets
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Screenshot%20(32).png)

# NodeJS
## About Node.JS : 
NodeJS is an open source server environment which is free and runs on various platforms(cross platform). 
* NodeJS executes the clients requests asynchronously without blocking the client for further requests.
* NodeJS runs single-threaded, which is very memory efficient. 
* NodeJS eliminates the waiting time of the request.

1. Downloaded NodeJS from https://nodejs.org/en/
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/NodeJS1.png)

2.Verified NPM and Ionic installations using CMD
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/npm.png)
![](https://github.com/pradeepika1997/ASE_LAB1/raw/master/Screenshots/Ionic.png)
