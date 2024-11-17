slip-1 git hub [1.1,15.2]

1.mkdir myproject
2.cd myproject
3.touch sample.py
4.notepad sample.py
5.git init
6.git add sample.py
7.git status
8.git commit -m "hey"
9.notepad sample.py
10.git add sample.py
11.git commit -m "git"
12. git status
13.git log
14.git remote add origin (github -link)
15.git push -u origin master

[same as above then next steps] 
slip-3.2,19.2,5.2,20.2


1.git checkout -b feature -branch
2.notepad main.py
#code to update
print("Feature branch changes")
3.git add main.py
4.git commit -m "Added feature branch changes"
5.git push -u origin feature--branch
6.git checkout master
7.git merge feature-branch
8.git push origin master
9.git log
10.git log --oneline
11.git log --graph --oneline

