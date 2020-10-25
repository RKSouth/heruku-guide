# Heroku Use Guide
## A simple guide on the basic process for setting up heroku

Create your deployed site BEFORE you start your project (to track your commits effectively)

Please do not forget to create a .gitignore for your assignments, and in them add:
.DS_Store
node_modules
package-lock.json

If you want to set up heroku to work with mysql there are additional steps that aren't included (you probably want to find those first)

## Table of Contents
* [Basic Proccess](#Basic_Proccess)
* [Usage](#Usage)
* [Author](#Author)
* [Credits](#Credits)

## Basic_Proccess

1. Set File Name by creating github repo
2. Clone github repo to file on your computer
3. Open your file with vs code, then open your terminal
4. In the terminal type in rm -rf .git (enter)
5. ls -la (enter) to make sure .git is gone
6. git init (enter)
7. git add . (enter)
8. git commit -m"init commit" (enter)
9. heroku login (enter)
10. type in a letter to be redirected to a log in
11. heroku create --2 urls should appear (save them)
12. git push origin master
13. git push heroku master

## Each time you want to commit again

1. git add . (enter)
2. git commit -m"your changes"
3. git push origin master
4. git push heroku master

## If you have problems with 3/4 (getting errors) you can:
1. git pull and then get push again

or

1. git checkout -b masterbranch
2. git push herko masterbranch

this resets the master branch - you may need to go into your github settings under branches and reset your branch

or
1. git remote add origin https:yourrepofilename
2. git push origin maset

## Usage

For anyone who can't keep track of all the step by step guides and hold them in their head at once. 

## Author

Rachael Kelm-Southworth

* [linkedin](https://www.linkedin.com/in/rachael-kelm-southworth-87a3831b3) 

* [github](https://github.com/RKSouth/)

* [portfolio](https://rksouth.github.io/responsive_portfolio/)