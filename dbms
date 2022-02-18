#!/usr/bin/bash

#This is part One that deal with directory

#fundamental knoledge for user
#-----------------------------
tput setaf 1 #1 for red
tput bold
echo  Hello, This is Database Managment System
echo 'Created Using Bash Script'
tput sgr0

function printScreen(){
printf '\nChoose:
 1) Create Database
 2) List Database
 3) Connect to Database 
 4) Drop Database 
 5) Exit \n'
}

while(true)
do
printScreen   #note, we dont use () after function name
read num
case $num in
1) source ./ForDirectory/Create
;;
2) source ./ForDirectory/List
;;
3) source ./ForDirectory/Connect
;;
4) source ./ForDirectory/Drop
;;
5) 
break
;;
*)
tput setaf 1 
echo 'This Is Not In The List'
tput sgr0 
;;
esac

done

