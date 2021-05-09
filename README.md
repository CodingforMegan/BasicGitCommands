Exercises on GitHub

Be sure to study the exercises we do in class and edit/play with them to understand how C++ works. The first time, you need to clone the repo, as I explained in class:

git clone ***https://github.com/pcc-cs/cs-003a-spring-2021-exercises***(Links to an external site.) Exercises
This will create a local repo on your computer under the folder Exercises (you can name it anything, but I recommend names that correspond to the repo name). You only need to clone once. To pick up subsequent changes from classes, you need to pull from the repo. Go "inside" the Exercises folder (using the cd command) and pull:

******git pull origin master*******



**************************
How to push code to GitHub? There are 3 steps:

***git add .***

***git commit -m "Your commit message here, to describe what you're committing"*****
****git push origin master****
That's basically it. git add will move all the changes in your folder to the staging area. Then git commit will "commit" so the staged changes re integrated into the repo. Finally, git push will "push" the changes to GitHub so it's in sync with what you have locally. I will be looking at what's on GitHub, so if you're new to this, go directly to GitHub and double-check that your changes got pushed.

Like with bazel tests, be sure to do all this from the root folder of the repo (e.g., where the WORKSPACE file is located for the projects). Also, the first time you commit on your system, you may be asked to add your name and email (so we can tell who committed) - follow the directions.
