# Lecture 6 Git-1
### Version Control and Collaboration
- It's essential to use a version control system for sofrware development and other documentation works.   

### Changes vs Snapshots   
- Changes: storing data as changes to the base version   
- Snapshots: storing data as snapshots   

### Local, centralized, and Distributed Version Control   
- Local: version control occurs only within the computer   
- Centralized: computers connect to the center   
- Distributed: computers connect not only centrally but also between computers    

### Three Stages in Git   
- ***Modified(Working Directory) \- Staged(Staging Area) \- Comitted(git directory)***      
- Modified \-\> Staged: stage fixes      
- Staged \-\> Comitted: commit   
- Comitted\-\> Modified: checkout the project   

### Installing Git   
- Linux/Mac/Windows(check pre-installed version)   
```sh
$ git --version
git version 2.25.1
$
```
- Linux(install on a Debian-based distribution)   
```sh
$ sudo apt install git-all
```
### Git config: First-time setup   
1. System level: --system option. Affects all uses and repositories on the system   
2. Global(user) level: --global option. Affects all repositories of a current user   
3. Local level: --local option. Specific to the current repository   
- system \-\> global \-\> local   

### Intializing a Repository in an Existing Directory   
```sh
$ git init
```
### Checking Repository Status   
```sh
$ git status
```
### Adding a new file to be staged(tracked)   
```sh
$ git add[file_name]
$ git add .
```
### Unstaging a file   
```sh
$ git rm -cached [file_name.txt]
rm 'file_name.txt'
```
### Ignoring a file   
```sh
$ git nano .gitignore file
```
### Commit   
```sh
$ git commit -m "commit message"
```
### Change branch name   
```sh
$ git branch
$ git branch -m master main
```
