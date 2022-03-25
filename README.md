# Demo_Smit
This Repository is for only for learning perpose 

## CONFIGURE TOOLING

```sh
>> $git config --global user.name "smit"
 ```
- This command is use to attached the name of user who 
   commit
- In abow case its smit


```sh
>> $git config --global user.email "development0261@gmail.com"
 ```
- This command is use to attached the email of user who 
   commit
- In abow case its development0261@gmail.com

## CREATE REPOSITORIES

```sh
>> $git init
```
- To create git Repository or initialize project to a git Repository


```sh
>> $git clone https://github.com/development0261/Demo_Smit.git
```
- to download the Hole project that exist in "Demo_Smit" Repository

## MAKE CHANGES

```sh
>> $git status
```
- It gives the all newly modefied or created file list 
   that need to commit on git
- if you familiar with Django so it work similer as 
   makemigrations

## REFACTOR FILENAMES
```sh
>> $git rm hello.html
-  This command is use to delete from current Repository as well as delete from our local machine directory
```

```sh
>> $git rm --cashed hello.html
-  This command is use to delete from current Repository but not from our local machine directory 
```

```sh
>> $git mv hello.html index.html
-  This command is use to Rename file hello.html to index.html

```
## REVIEW HISTORY
```sh
>> $git log
-  It gives us list of all commits history of current branch
```