# LECTURE NOTE 4
##### 202235873 유도연    
---
### Linux
> Linux: Open-sourece Unix-like operating systems and kernels, first-released by Linnus Torvalds in 1991

### Kernal and Shell
Kernel: Core of OS that controls and communicates with hardware resource     
Shell: Interface that allows users to communicate with kernal: bash, zsh, ...   
Users runs applications and give commands through shell

### CLI(Command Line Interface) vs GUI(Graphical User Interface)    
CLI:   
Have to remember commands    
GUI:   
Easy to use and Intuitive
### Shell command
---

1. pwd   
```sh
$ pwd
/home/youngmin
$
```
2. cd and ls   
```sh
$ ls
Backup Documents Lectures Research
Dataset Downloads Public
Desktop GitHub OSS
$ cd OSS
$ pwd
/home/youngmin/OSS
$ ls
neuralintlab transformers
```
- arguments:   
[directory name]   
/ root   
. current directory   
.. upper-level directory   
~ home of current user   
/[directory name]: absolute path   
./[directory name]: relative path   
../[directory name]: relative path   
- options:
 \-l: show detailed information(long format)   
\-lh: same as above, but size in units  
3. clear   
clean your terminal   

---
### Tip
--- 

1. Autocompletion   
: write cd n + Press "tab" key    
2. Past commands   
: Press "up arrow" key   

---
### Manipulation
--- 

1. cp   
: copy files and directories   
```sh
$ cp module.py backup_module.py
$ cp -r ../neuralintlab
```
2. mv   
: move files and directories or rename them   
```sh
$ mv file1 file2
```
3. rm   
: delete files and directories **permantely and irreversevely**   
4. mkdir   
: make a new directory   
```sh
$ mkdir new_directory
```
4. Help command: help, man
5. Exiting terminal: exit
```sh
$ exit
```

---
