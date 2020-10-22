# Heroku Use Guide
## A simple guide on the basic process for setting up heroku

## Table of Contents
* [Basic Proccess](#Basic_Proccess)
* [Usage](#Usage)
* [Author](#Author)
* [Credits](#Credits)
* [License](#License)


Create your deployed site BEFORE you start your project (to track your commits effectively)

## Basic_Proccess

1. Set File Name by creating github repo
2. Clone github repo to file on your computer
3. Open your file with vs code, then open your terminal
4. In the terminal type in rm -rf .git (enter)
5. ls -la (enter) to make sure .git is gone
6. git init (enter)
7. git add . (enter)
8. git commit -m"init commit" (enter)
9. heroku create --2 urls should appear (save them)
10. git push origin master
11. git push heroku master

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

this resets the master branch

## Usage

For anyone who can't keep track of all the step by step guides and hold them in their head at once. 

## Author

Rachael Kelm-Southworth

* [linkedin] (https://www.linkedin.com/in/rachael-kelm-southworth-87a3831b3) 

* [github] (https://github.com/RKSouth/)