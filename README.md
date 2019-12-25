# Git Documentation

***After installation has been done, you must write your username and email for git identification***    
```
git config --global user.name "Nama / Username"  
git config --global user.email yourmail@gmail.com
```  

It usefull to identify who used git / who was commit.   <br><br>

  
***Checking Configuration***
``` 
git config --list   
```      
or
```
git config --global --list
```
<br><br>
***How to define folder or file on .gitignore***  

Define 'test' folder with all files inside :

```
test/*
```

Define file spesifically :  

```
index.php  
```

Define all file with .txt extension :  

```
*.txt
```
<br><br>
***How to create repository***
```
git init
```
Make sure, that you are on the right directory.
<br><br>

## The main command on git :
When you are working on project, this following command will used often. 

If you have github account, you can connect into your online repository on github with this command :
```
git remote add origin https://github.com/userName/Folder-proyek1.git
```

use this command to check your file / folder status :
```
git status
```  
If your file have red color and "untracked", "deleted" or "modified" status, it means you must add it to your repository with this command :
```
git add .
```
Noted : 
- *untracked* : your file has not detected on git repository.
- *deleted* : your file has been deleted on your folder.
- *modified* : you have modified that file.  
<br>
After all files / folder have been added into your repository, just check your repository status again. If your file / folder have green color, it means you can commit your file / folder into your repository. Use this command to commit your project :  
```
git commit -m "Your message / note"
```
Make sure that you write your message, because it useful when you work together with your team or friend.    
<br>
After that, if you want to upload your updated repository into your github (online repository) you can use this command :  
```
git push -u origin master
```
Noted : "master" is your branch, if you want to push into the different branch, you could change that with your branch.  


