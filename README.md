---
title: My new post
date: 2017-02-12 17:15:35
tags:
---
# README #

This project is intended to allow new devs to learn how to use git and pull request methodology.

## Pull request ##

**_1._** You should create a branch (Always the branch name must has the initials of your name **/** the ticket, for example **lg/readme**)  
``` 
git checkout - b branchname 
```  
**_2._** Optional, you can create a message referring to the action.  
``` 
git commit -a -m "Your message"
```  
**_3._** You should upload changes using  
``` 
git push origin branchname
```  
**_4._** You should visit [bitbucket](https://bitbucket.org/account/signin/) web page.  
**_5._** Here you find the option **Create pull request** you should click on the option.  
**_6._** You should choose the brand, write a title and write the description (Always you must specify what is the development and how can proof the functionality).  

## Git ##
[comment]: # (This actually is the most platform independent comment)
**Change the name of a branch**  
``` 
git branch -m oldbranchname newnbranchname
```  
**Delete a branch**  
```
git branch -d branchname
```  
or  
``` 
git push origin: branchname
```  
**List all the branches**  
``` 
git branch
```  
**Switch from one branch to another**  
```
git checkout branchname
```  
**Add all files**  
```
git add .
```  
**Add one file**  
```
git add filename
```  
**Clone a repository**  
```
git clone
```  
**List the files you've changed**  
```
git status 
```  
**Create a repository**  
If you create a repository you have the option to upload your project with the commands:  
```
git remote add origin
```  
It is for choose location in your repository, it can take the remote name or a remote URL.  
``` 
git push -u origin master
```  
It is for complete the upload process.  
**Config user**  

First time, you should config your username and your email  

|**Username**                             |**Email**                                 |
|:---------------------------------------:|:----------------------------------------:| 
|git config --global user.name "Your name"|git config --global user.email Your email |