# How to git with GitHub?

##Setup **local** git: (If you never setup git at the current computer)
```
$ git config --global user.name "Benson516"
$ git config --global user.email "benson516@hotmail.com"
```

##Create new repository (**local**)
Initiate the project directory as a git repository
In the project directory:
```
$ git init
```

Associate this repository to the remote repository at GitHub
```
$ git remote add origin https://github.com/Benson516/Hello_repo.git
```

##Synchronize between **remote** Github repository and the **local** git repository

- **remote** Github repository ---> **local** git repository
    ```
    $ git pull origin master
    ```
    or simply copy the **remote** repository to the **local** filesystem
    ```
    $ git clone https://github.com/Benson516/Hello_repo.git
    ```

- **local** git repository ---> **remote** Github repository 

    ```
    $ git add .
    $ git commit -m "Backup"
    $ git push origin master
    ```
