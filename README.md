1- git init task-manager
2- cd task-manager
3- echo "- Learn Git Basics" >> tasks.txt
4- echo "- Set up Git repository" >> tasks.txt
5- git add tasks.txt
6- git commit -m "File added"
7- git checkout -b feature/add-tasks
8- echo "- Practice Git branching" >> tasks.txt
9- git add .
10- git commit -m "File modifed for secon branch"
11- git checkout master
12- git checkout -b feature/remove-tasks
13- nano tasks.txt
14- git checkout master
15- git merge feature/add-tasks
16- git checkout feature/add-tasks
17- git add .
18- git commit -m "merge B1"
19- git checkout feature/remove-tasks
20- git add .
21- git commite -m "Task deleted"
22- git checkout master
23- git merge feature/remove-tasks
24-  git merge feature/add-tasks
25- nano show tasks.txt
26- git status
27- git add .
28- git commit -m "Merged"
29- git checkout -b feature/update-tasks
30- echo "- Review Git merge and rebase" >> tasks.txt
31-  echo "- Review Git merge and rebase" >> tasks.txt
32- git add .
33- git commit -m "Changes Added"
34- git checkout master
35- git rebase feature/update-tasks
36- echo "- Some incorrect task" >> tasks.txt
37- git add tasks.txt
38- git commit -m "Add incorrect task"
39- git log
40- git revert 3d07eeddefaa0545eba79b1b908f7f478cccb8d2
41- git add.
42- git commit -m "Upload to repo"
43- git remote add origin https://github.com/MaymonahAlharbi/Day03Project.git
44- git branch -M main
45- git push -u origin main

