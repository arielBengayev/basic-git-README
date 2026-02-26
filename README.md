## ssh key setup
open cmd and run
```
ssh-keygen
```
press enter for all and run
```
cd .ssh
```
in ssh package run
```
dir
```
copy the id.pub and run
```
type id.pub
```
copy the ssh key and go to -> https://github.com/settings/keys

press on new SSH key and past your ssh key

---

## personal access token setup
go to -> https://github.com/settings/tokens

1.press on personal access token -> tokens (classic)

2.press on generate new token

3.choose generate new token (classic)

4.choose all scopse and press generate

---

## open new repo
1. choose a repo name
2. press on .gitignore and choose your language
3. press on create repository

---

## clone project with https 
1. press on code -> https
2. copy the link
3. open the cmd
4. go to desktop
```
cd c:\Users\pc name\Desktop
```
run the command
```
git clone your https link
```
now you can see the folder in desktop

open the folder -> open the readme file with text editor

make a change in the file and create new text file

to see the status run
```
git status
```
run
```
git add .
```
run to see new status
```
git status
```
run
```
git commit -m "first change"
```
```
git push
```
