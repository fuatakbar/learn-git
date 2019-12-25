# Git Documentation

***After installation has been done, you must write your username and email for git identification***    
```
git config --global user.name "Nama / Username"  
git config --global user.email fuatakbars@gmail.com
```  

It usefull to identify who used git / who was commit. 

***Checking Configuration***
``` 
git config --list   
```      
or
```
git config --global --list
```

***How to define folder or file on .gitignore***  

define 'test' folder with all files inside :

```
test/*
```

define file spesifically :  

```
index.php  
```

define all file with .txt extension :  

```
*.txt
```

***How to create repository***
```
git init
```

