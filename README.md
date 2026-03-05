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

to see the status go to your project folder
```
cd folder name
```
run
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

## creat branchs 
1. in your project repo press on main/master
2. creat new branchs b1 - task1
3. press on branch name and go to main/master
4. creat another branch b2 - task2
5. go to intellij, press on the blue arrow and choose Rebase
6. press on main in the right side -> choose b1 -> checkout
7. now you on branch b1

---

## commit and push from branch
1. make a change on branch b1
2. commit and push the changes
3. now you can see the changes on branch b1 only

---

## merge into main with pull request
1. go to main repo page (git-demo)
2. press on pull requests -> new pull request
3. in compare choose branch b1
4. press on create pull request
5. in conversation press merge pull request -> confirm merge
6. now you can see the changes in branch main but not in intellij
7. go to intellij and press on the blue arrow
8. now you can see on intellij

---

## resolve conflict
1. make a change on branch b2
2. commit and push the changes
3. press on compare & pull request
4. cant merge
5. go to intellij -> branch main -> and press on the blue arrow
6. go back to branch b2
7. press on main -> branch main -> merge main into b2 -> merge
8. now you can see the conflict
9. choose "hello from branch 2" with the arrows
10. change to "hello from branch 2 considering branch 1"
11. press the "X" in "hello from branch 1" and press apply
12. press on the graan arrow (push)
13. go to github repo -> compare & pull request -> create pull request -> merge pull request -> confirm merge

---

## adding a bad commit
1. go to intellij -> branch main
2. press on the blue arrow
3. add a bad commit in project
4. commit and push the changes
5. go to github repo to see the bad commit

 ---

 ## revert commit
1. press on git in intellij in the left side
2. press with the right button on the bad commit
3. choose revert commit
4. created a new commit that revert the bad commit
5. press on the green arrow (push)
6. go to github repo to see that now you dont have the bad commit

---

## compare changes with local
1. press on git icom in the left side
2. press with the right button on the commit that you want to compare
3. choose compare with local
4. in the new window (changes) choose the file you want to compare
5. now you can compare the changes with the current file

---

## compare with git history
1. go to file you want to compare
2. in the file press on the right button
3. choose git -> show history

---

## compare with branch
1. go to file you want to compare
2. in the file press on the right button
3. choose git -> compare with branch -> choose the branch you want to compare with
