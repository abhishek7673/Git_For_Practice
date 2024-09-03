# For Begineer
# A. Steps For Loading various files to GITHUB: 
.. I WILL BE DEMONSTRATING HOW I ACTUALLY DID ..
1. Create a new repository with any name.
2. Copy its web address
3. Open Git Bash in your system(need to install first), open it in file/folder where you want to store your projects in your system
4. Type git clone (paste the link copied in step 2)
5. Now it's done.
6. Now open your file with code editor such as vs code(i will be doing in it).
7. Code your project as you do ..., after coding
8. Type git add . (press enter)
9. Now Type git commit -m "first commit" press enter ("any message ")
10. Now Type git push press enter, it's done your project file folder is pushed on github.
    
# B. Steps when u already developed your project, now u wan tto push it on github.
1. Open github and create a new repository
2. Open the project in your VS Code. Open the new terminal
3. Type git init (Press enter)
4. Want to add READme file then type git add README.md (press enter)
5. Then Type git add . (press enter)
6. Type git commit -m "first commit" (press enter)
7. Type git branch -M main (press enter)
8. Type git remote add origin (repo link copied in step 2 of step A) (press enter)
9. Type git push -u origin main (press enter)
10. Its Done

# C. Steps If you want to collaborate in a project
1. Create another branch from main branch
2. IF you want to do things in group, need to approve collaborators. So
3. after step 1, click setting in the repo itself.
4. then collaborators and invite via their username, email.
5. they accept and yo go.
6. after they accept your invite. they will posses the same window for the particular project.
7. They will fork the project.

# D. Steps if you alter your project in editor , then hpw will u update.
1. open new terminal
2. clone this project in your system.
3. type git status
4. Do the changes whatever., add or edit
5. Type git add .
6. Type git commit -m "messge"
7. type git push
8. After pushing come to github, click on contribution drop down button
9. there will be 'create a pull request', click it
10. Owner will review it, then create pull request by adding some description.
11. Click merge pull request
