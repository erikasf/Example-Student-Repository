# Exercise Answers
##Beginner
1. Write the command that will allow you to navigate to two directories above your current directory. Study these examples: 
  ```
  Ryan@RyansLaptop ~/Coursework/Fall 2015/BIOL13/
  to
  Ryan@RyansLaptop ~/Coursework/
  cd ../../ or to move down the file tree in the reverse direction is 
  cd Fall2015/BIOL13/

  Steve@FamilyComputer ~/My Documents/Book Library/Francine Jay/The Joy of Less/
  to
  Steve@FamilyComputer ~/My Documents/Book Library/
  cd ../../ 

  ```
2. Write the command and flag that will list the files and directories inside of your current directory.
Current directory or path:
  ```
 Ryan@RyansLaptop ~/Coursework/Fall 2015/ 
 command.       flag	
 ***ls*** *** -a***(shows hidden files)
 			
  ```
3.  
  ```
 | Command | flag |
| ------ | ----------- |
|***ls*** | 
|       ||


  ```
4.
```
| Command | flag |
| ------ | ----------- |
|***ls*** | ***-l***
|       |expanded view|

5.
```
mkdir clean_code_examples
```
6.
```
touch anythingIlike.txt
```
7.
```
cat socks_to_buy.text
```
8.
```
pwd
```
9.
```
there are actually a few ways to discover that 
there is:
echo "$(whoami)"
or 
echo "$(id -u -n)"

10.
```
ls ../../
```

11.
```
touch list_of_best_cat_pictures.html
```
12.
```
cd: c/Users/Default/User/My_Documents
 ```
 13
 ```
 ping 8.8.8.8
 ```
 14
 ```
 command prompt: ~

 ```
 15
 ```

 NAME1 = ' RYAN
 '
 NAME2 = "SHARON"
  echo = "WELCOME, $(NAME1)"
 echo = "WELCOME, $(NAME2)"
 ```
16
```
cat tylers_favorite_songs.txt; sarahs_favorite_songs.txt

```
17
```
  man echo > ./echo_options.txt

  ```
  18
  ```
ping -c 2 127.0.0.1
  ```
  19
  ```
  ls *.md

  ```
  20
  ```
 remove(./yesterdays_todo_list.md)


##Intermediate

 1
 ```
 touch myname.md   
    echo "Erika Harvey" >> myname.md
    touch myfavoritefoods.md
    echo "tiriamisu,beer,steak" >> myfavoritefoods.md
    touch dreamproject.md
    echo "patient advocate portal" >> dreamproject.md
    touch music.md
    echo "Depeche Mode" >> music.md
    touch colors.md
    echo "indigo" >> colors.md
    ```
  2.
  ```
  ls -h | sort files > filesizes.txt
  ```
  3.
  ```
    mkdir backups
    mv backup1.tar.ga ./backups
  ```
  4.
  ```
 echo -e allnurse'\n' spotify '\n' > sites.txt
 ```
 5.
 ```
 curl -L http://study.moderndeveloper.com > study.html
 ```
 6.
 ```
 mkdir backups
 cd backups
 mv backup1.tar.gz ./backups
 mv backup1.tar.gz "$(date '=%ym%d%H%M').tar.gz
 ```
 7.
 ```
 wc -w dreamproject.md
 ```
 8.
 ```
 grep "\.js" study.html > javascripts.html
 ```
 9.
 ```
  cat *.txt | wc -w
      74
➜  
 ```
 10.
 ```
find  *.md *.html *.txt
 find  *.md *.html *.txt | tar -cvzf backups2.tar.gz 
 find . -name "*.md" "*.html" "*.txt" -delete
 
 ##Advanced
 
 1.
``
 
  






##Answers to questions
1. What is the cd?
    change directory. Changes the current working directory to the directory $DIR. In effect, moves you around the computer. For example to move into a directory or folder thats found in Documents you would use 
    cd Documents/practice or to go back home cd ~
2. What is the exit command
    When you are done wiht a terminal window or tab and ready to exit you use the exit command  which is ```$ exit```
    but when you want to quit the man pages you don't use exit you use :q for quit. 
    Bash's exit status is the exit status of the last command executed in the script.
3.pwd?
    pwd is an acronym for print working directory. the pwd is one of the most frequently used commands.
    it can be used to find the full path to the current directory which is just the directory that you are currently operating in . 
    Syntax is 
    ```
    pwd
    pwd [options]
    var = $(pwd)
    echo "The current working director $var"
    ```
    to print current dir. 
    ```
    $ pwd
    /user/underpaidnurse (is mine)
    ```
    

  