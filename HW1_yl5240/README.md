# PUI2017_yl5240
## 1.create a directory on my computer 
the path of the directory is /Users/apple/Desktop/PUI2017

## 2. creat an environmental variable and an alias in .bash_profile
### 1) type:
> nano ~/.bash_profile
### 2) create an environmental variable $PUI2017
> export PUI2017=/Users/apple/Desktop/PUI2017
### 3) use the environmental variable to create an alias pui2017
> alias pui2017="cd $PUI2017"
### 4) type:
> source ~/.bash_profile
### 5) take the screenshot of .bash_profile:
![bash_file](https://github.com/picniclin/PUI2017_yl5240/blob/master/screenshot/1.png)

## 3.check the alias path to the directory
### 1) show the present working directory
> pwd 
### 2) use the alias to move to the directory created
> pui2017 
### 3) show the new directory
> pwd
### 4) take the screenshot:
![pwd](https://github.com/picniclin/PUI2017_yl5240/blob/master/screenshot/2.png)

## 4.upload to github
### 1) create a new github repo
https://github.com/picniclin/PUI2017_yl5240
### 2) upload the screenshots to the directory
