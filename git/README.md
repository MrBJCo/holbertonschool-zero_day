#  Git Projects

# Task

## Repo-session 
Create a new directory called git in your repo.

Make sure you include a not empty README.md in your directory:
-  at the root of your repository
-  AND in the directory git
And important part: **Make sure your commit and push your code to Github - otherwise the Checker will always fail.**
<br><br/>


Repo:
- GitHub repository: **holbertonschool-zero_day**
- File: **README.md**

<br>
## Coding fury road
For the moment we have an empty project directory containing only a README.md. It’s time to code!

- Create these directories at the root of your project: bash, c, js
- Create these empty files:
  - c/c_is_fun.c
  - js/main.js
  - js/index.js
- Create a file **bash/best** with these two lines inside: **#!/bin/bash and echo "Best"**
- Create a file **bash/school** with these two lines inside: **#!/bin/bash and echo "School"**
    Add all these new files to git
    Commit your changes (message: <u>“Starting to code today, so cool”</u>) and push to the remote server


Repo:

- GitHub repository: **holbertonschool-zero_day**
- Directory: **git**
- File: **bash/best, bash/school, c/c_is_fun.c, js/main.js, js/index.js**
<br>
## Collaboration is the base of a company
A branch is like a copy of your project. It’s used mainly for:
- adding a feature in development
- collaborating on the same project with other developers
- not breaking your entire repository
- not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch **update_script** and in this branch:
- Create an empty file named bash/98
- Update bash/best by replacing echo "Best" with echo "Best School"
- Update bash/school by replacing echo "School" with echo "The school is open!"
- Add and commit these changes (message: “My personal work”)
- Push this new branch <a href="https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository">Tips</a>

Perfect! You did an amazing update in your project and it’s isolated correctly from the **main** branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:
- Change branch to main
- Update the file **bash/best** by replacing echo "**Best**" with echo "**This School is so cool!**"
- Delete the directory **js**
- Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

Repo:
- GitHub repository: **holbertonschool-zero_day**
- Directory: **git**
- File: **bash/best, bash/school, bash/98**
<br>
## Collaboration: be up to date 
Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task **– and only for this task –** please update your file **README.md** in the main branch from GitHub.com. It’s the **only time** you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:
- Get all changes of the main branch locally (i.e. your README.md file will be updated)
- Create a new file **up_to_date** at the root of your directory and in it, write the git command line used
- Add **up_to_date** to git, commit (message: “How to be up to date in git”), and push to the origin

Repo:
- GitHub repository: **holbertonschool-zero_day**
- Directory: **git**
- File: **README.md, up_to_date**

\**Finish the organization README.md*\
