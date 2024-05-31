## 01 Setting up name and email address
If you've never used Git before, the first step is to set up your name and email address.

Run
```
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"
```
## 02 Default branch name
We will use main as the default branch name. To set this up, run the following command:

Run
```
git config --global init.defaultBranch main
```
## 03 Line endings treatment
 for users of Unix/Mac:
 
Run
```
git config --global core.autocrlf input
git config --global core.safecrlf warn
```
For Windows users:

**Why are you using windows ?**

