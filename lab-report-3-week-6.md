# Lab Report 3  

## Streamlining ssh Configuration 
1) Created a config file withn the `.ssh/` directory and added:  

`Host ieng6`  
    `HostName ieng6.ucsd.edu`  
    `User cs15lsp22aio (use your username)`  

 <img src='3 Group Options/config.PNG' title='config.PNG' width='' alt='config.PNG' />   
 
2) Running `ssh ieng6` to quickly login  

 <img src='3 Group Options/ssh ieng6.PNG' title='ssh ieng6.PNG' width='' alt='ssh ieng6.PNG' />  
 
3) Running `scp` along with `ieng6` to quickly copy files over  
 <img src='3 Group Options/scp ieng6.PNG' title='scp ieng6.PNG' width='' alt='scp ieng6.PNG' />  

## Setup Github Access from ieng6  

1) Key-Genned a ssh key on the ieng6 and pasted the `.pub` code into GitHub  

 <img src='3 Group Options/GitHub ssh.PNG' title='GitHub ssh.PNG' width='' alt='GitHub ssh.PNG' />  
 
2) File within ieng6 that contains the ssh key

 <img src='3 Group Options/id_rsa.PNG' title='id_rsa.PNG' width='' alt='id_rsa.PNG' />  
 
3) Downloaded a directory with the ssh link and pushed from the ieng6 server  

 <img src='3 Group Options/Pushed to Origin on ieng6.PNG' title='Pushed to Origin on ieng6.PNG' width='' alt='Pushed to Origin on ieng6.PNG' />  
 
4) Commit is shown on the GitHub website  

 <img src='3 Group Options/Git Push From remote.PNG' title='Git Push From remote.PNG' width='' alt='Git Push From remote.PNG' />  
 
[Link to Commit](https://github.com/kevku/markdown-parser-mine/commit/58c3befb8de886b1f3d185d6415faac9bacd5b16)  
 

## Copy whole directories with `scp -r`  

1) Entered `scp -r . ieng6:~/markdown-parse; scp -r *.java *.md lib/ ieng6:markdown-parse; ssh ieng6` in Shell (Local PC)

This is to copy all the files in a directory into a new folder on the ieng6 server and logs me into my ieng6 account  

 <img src='3 Group Options/One line for Shell.PNG' title='One line for Shell.PNG' width='' alt='One line for Shell.PNG' />  
2) Entered the commands to compile and run the java file in ieng6  

 <img src='3 Group Options/One line for Bash.PNG' title='One line for Bash.PNG' width='' alt='One line for Bash.PNG' />  
