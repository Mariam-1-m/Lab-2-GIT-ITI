![Programing IMG](images/img1.jpg "image 1")

git init
git add .
git commit -m 'first commit lab 2'
git remote add origin git@github.com:Mariam-1-m/Lab-2-GIT-ITI.git
git push -u origin main

git branch test
git branch dev

git switch test
git status

here we created the file
git add test.js 
git commit -m 'add test brach file'



git switch dev
git status

here we created the file
git add dev.js 
git commit -m 'add dev brach file'

git switch dev 
git merge test

git switch main
git merge dev

git push origin main

q4- git branch -d test  
git push origin :test
git branch -d dev
git push origin :dev
q5- git stash 
git stash pop


git tag -a v1.0 -m 'version 1.0'
git push origin main
git tag 

git tag -d v1.0
git push origin main

add img in my structure then add this path to readme file 