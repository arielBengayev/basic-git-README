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

## personal access token (https) setup
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
1. open the project repo on github
2. press on code -> https
3. copy the link
4. open the cmd
5. go to desktop
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
if you need to sign in choose token and past your personal access token

now you can see the changes on github

---

## clone project with ssh
open the cmd and remove the clone folder
```
rd /s /q folder name
```
1. open the project repo on github
2. press on code -> ssh
3. copy the link
4. open the cmd
5. go to desktop
```
cd c:\Users\pc name\Desktop
```
run the command
```
git clone your ssh link
```
if you need enter yes

now you can see the folder in desktop

---

## commit and push from intellij
1. open the folder in intellij
2. go to -> https://start.spring.io/ and create new project
3. copy all new project files to the repo project from intellij
4. press on maven/gradle load!!! if not show restart intellij
5. run the project -> src -> main -> java -> DemoAplication
6. press on commit in the left side
7. enter -> commit from intellij and press on commit
8. press on the green arrow for push to github
now you can see the changes on github

---

