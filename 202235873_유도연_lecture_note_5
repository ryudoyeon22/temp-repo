# lecture5: CLI-2    
### I/O Redirection: Standard Output     
---

- \>: creates and saves the output in a file    
```sh
$ ls -lh > filename.txt
```
- cat: displays the content of a text file   
```sh
$ cat filename.txt
``` 
- \>>: appends output to an existing file or creat and write to a new file    
```sh
$ ls -lh >> filename.txt
```

---
### I/O Redirection: Standard Input   
---

- <: redirects input from a file    
- You can mix "<" and ">" together in a single line.   
```sh
$ sort < words.txt > sorted_words.txt 
```

---
### Pipelines "|"   
- Pipeline feeds output of previous command to input of next command    
```sh
$ ls -lh | less
$ ls | wc -l
```
### Expansion   
- Special characters expand its meaning when given to shell commands    
```sh
$ echo
$ echo * 
$ echo ~
```
### Permissions   
- owner / group / others
- rwx: Read, write and execute permission
    > ex) \-rwxr\-xrw\-:    
    > **owner**: can read, write and execute   
    > **group**: only can read and execute    
    > **others**: only can read and write    
### Changing Permissions
- "chmod" changse permissions   
- rwx = 111 in binary = 7   
- rw\- = 110 in binary = 6
```sh
$ chmod 644 words.txt
```
### Superuser
- A superuser has all system administation authority   
- Some commands need superuser's privillages   
- Put "sudo" before the command if you are a superuser   
- Type "exit" to get out of a superuser session    
```sh
$ sudo some_command
Password for me:
```
### Text Editors
- yi, yim   
- Emacs   
- nano   
- gedit   
- kwrite   
### Shell Script
```sh
$ nano myscript.sh
```
