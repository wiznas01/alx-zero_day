This task was successfully completed by Aminu Nasiru Yaro

Step 0 - Create an account on GitHub [if you do not have one already]
You will need a GitHub account for all your projects at ALX.

Step 1 - Create a Personal Access Token on Github
To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

Step 2 - Update your profile on the Intranet
Update your Intranet profile by adding your Github username here
If it’s not done the Checker won’t be able to correct your work

Step 3 - Create your first repository
Using the graphic interface on the github website, create your first repository.
Name: alx-pre_course
Description: I'm now a ALX Student, this is my first repository as a full-stack engineer
Public repo
No README, .gitignore, or license

Step 4 - Open the sandbox
On the intranet, just under the task, click on the button "sandbox" and run to start the machine.
Once the container is started, click on "webterm" to open a shell where you can start work from.

Step 5 - Clone your repository
On the webterm of the sandbox, do the following:
Clone your repository
Replace {YOUR_PERSONAL_TOKEN} with your token from step 1
Replace {YOUR_USERNAME} with your username from step 0 and 1

Step 6 - Create the README.md and push the modifications
Navigate to this new directory.
Create the file README.md with the content My first readme.
Update your git identity
Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin

1. Repo-session
Create a new directory called 0x01-git in your alx-zero_day repo.
Make sure you include a non empty README.md in your directory:
at the root of your repository alx-zero_day
AND in the directory 0x01-git
And important part: Make sure your commit and push your code to Github - otherwise the Checker will always fail.

2. Coding fury road
For the moment we have an empty project directory containing only a README.md. It’s time to code!
Inside 0x01-git:
Create these directories at the root of your project: bash, c, js
Create these empty files:
c/c_is_fun.c
js/main.js
js/index.js
Create a file bash/alx with these two lines inside: #!/bin/bash and echo "ALX"
Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
Add all these new files to git
Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

3. Collaboration is the base of a company
A branch is like a copy of your project. It’s used mainly for:
adding a feature in development
collaborating on the same project with other developers
not breaking your entire repository
not upsetting your co-workers
The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.
For this project, create a branch update_script and in this branch:
Create an empty file named bash/98
Update bash/alx by replacing echo "ALX" with echo "ALX School"
Update bash/school by replacing echo "School" with echo "The school is open!"
Add and commit these changes (message: “My personal work”)
Push this new branch Tips
Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch.
Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:
Change branch to main
Update the file bash/alx by replacing echo "ALX" with echo "ALX School is so cool!"
Delete the directory js
Commit your changes (message: “Hot fix”) and push to the origin
Ouf, hot fix is done!

4. Collaboration: be up to date
Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.
For this task – and only for this task – please update your file README.md in the main branch from GitHub.com. It’s the only time you are allowed to update and commit from GitHub interface.
After you have done that, in your terminal:
Get all changes of the main branch locally (i.e. your README.md file will be updated)
Create a new file up_to_date at the root of your directory and in it, write the git command line used
Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin

