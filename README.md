![Programing IMG](images/img1.jpg "image 1")

# Lab 2 - Git & GitHub Exercises

1- Create a new project on your local machine, then push it to your remote repo.
```bash
git init
git add .
git commit -m 'first commit lab 2'
git remote add origin git@github.com:Mariam-1-m/Lab-2-GIT-ITI.git
git push -u origin main

2-Create two branches (dev & test) then create one
file on each branch, and push this changes to the remote repo.
git branch test
git branch dev
git push origin test
git push origin dev

3-Merge this changes on Main branch and then push it to your
remote main branch.
git switch test
git status
# here we created the file
git add test.js 
git commit -m 'add test branch file'

git switch dev
git status
# here we created the file
git add dev.js 
git commit -m 'add dev branch file'

git switch dev 
git merge test

git switch main
git merge dev

git push origin main

4-Tell me how to remove them locally and remotely.
git branch -d test  
git push origin :test
git branch -d dev
git push origin :dev

5-Tell me how to checkout another branch without commit changes
git add .
git stash
git switch test 
git switch main
git stash pop

6-Tell me how to checkout another branch without commit changes
git tag -a v1.0 -m 'version 1.0'

7-Push it to the remote repository.
git push origin main

8-Tell me how to list tags.
git tag 

9-Tell me how to delete tag locally and remotely.
git tag -d v1.0
git push origin --delete v1.0



10-Add an image in the README.md file.
add img in my structure then add this path to readme file 
![Programing IMG](images/img1.jpg "image 1")