# Day 1 – Linux File System Basics

## What I learned
- Linux uses a hierarchical file system.
- Everything starts from root directory (/).
- Different commands for file system

## Commands Practiced
pwd
ls,  
ls -l, 
cd /, 
cd ~, 
cd .., 
cd path, 
tree, 
mv (move), 
mv (rename), 
cp, 
mkdir,  
touch (create file), 
rm (delete file), 
rm -r (delete directory), 
echo 'text' >, 
echo 'text' >>, 
cat (view file content), 

## What I understood in simple words
Linux file system is like a tree. Everything starts from /. 

## Problems I faced
I was confused between / and /root.\n
move file from directory d1 to d2(both inside "D") while inside d1. I was trying mv del.txt d2/ or d2. \n

## How I fixed them
Learned that / is system root, ~ is home of user.\n
giving the path to move helps(mv del.txt ../d2).\n

## Surprises
tree command counts (.) for total directories\n
I can directly create a file or folder inside an intended directory from anywhere by giving the path before its name.\n
command mv del.txt d2 it changes file name to d2 but if there is already a dir "d2" then it moves the file there\n
