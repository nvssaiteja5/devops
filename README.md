# GIT INTRODUCTION
### **Definition**
GIT it is a version control system used to work on a set of files and track the changes in the files with a group of  people of individual

* Git was developed by **LINUS TORVALS** in **2005**

### Getting started 
* **Git Repository** it is a place where all files are stored and  git tracks all the  changes made to a particular file 
* To create a repository 


### Git configuration
* To configure git through command line <br/>
`git config --global user.name "name" `<br/>
` git config --global user.gmail "mail id"` <br/>

* To verify the configurations  <br/>
`git config --global --list`


## Git commands 
### **Git Clone** 

`https://github.com/nvssaiteja5/devops` <br/>
* It will copy the repository into the current director
* this command will copy all the files in the **devops** repository to your current directory

###  Git  init 

`git init ` <br/>
* It converts the present directory into git repository <br/>
* It will also  add a **.git** folder to your directory  which contains git records and git configuration files


### Git add

 `git add .`  <br/> 
* It will add all the files to the staging area  <br/> <br/>
 `git add <file_name>` 
* This will add a specified file to the staging area <br/> <br/> 
 **Staging area**  <br/>
* It is a place where we save the file and modify the file 
 before moving to the commit stage
 ### Git push
 `git commit -m "your commit message here"` <br/>
 * This command will push all the files  from staging area to the local repository
 
 
 
