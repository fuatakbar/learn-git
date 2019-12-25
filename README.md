# Git Documentation

***Setelah Installasi Selesai***    
```
git config --global user.name "Nama / Username"  
git config --global user.email fuatakbars@gmail.com
```  

Digunakan untuk mengisi informasi identitas pengguna git.  

***Memeriksa Konfigurasi***
``` 
git config --list   
```      
atau
```
git config --global --list
```

***Mendefinisikan folder dan file dalam gitignore***  

mendefinisikan folder test dengan semua file didalamnya :

```
test/*
```

mendefinisikan file index.php :  

```
index.php  
```

mendefinisikan semua file yang berextensi .txt :  

```
*.txt
```

***Membuat Repositori***
```
git init
```

