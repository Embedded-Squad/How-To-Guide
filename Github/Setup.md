# Setting Up Github

Basic docs on how to setup Git for your pc

# Installation of Git

- Download git from the following link:
  `https://git-scm.com/downloads`
- Follow the installation wizard and intall git
- Git is configured in your PC

# Setting Up Github

- Setup Github account from the website:
  `https://github.com/`
- Click on your image and go to `Your Repositories`
- Click on `New` to create a new repository
- Enter the name of repository you want
- Click on `Create Repository`
- Multiple code snippets are shown, copy the first code snippet
- Now create/open directory in which you want to initialize and link that repository
- Open command prompt and cd(change directory) to path of selected directory
- Now paste the copied code snippet in cmd line
- You may be asked to authorize then click on sign in with browser and your default browser window will open and it will be automatically authorized.
- Your github is initialized.

# Basic Commands you can use with Github CLI

- `git status` -> to see if there are some uncommitted or unadded changes.
- `git add .` -> to add all changes to be commited.
- `git commit -m "Commmit Message"` -> To commit the changes that are added using above command.
- `git push -u origin <branch-name>` -> Push your code to online github repository that you created.
- `git pull` -> To bring in any changes that are done on repository in github.
- `git checkout <branch-name>` -> To move to a different branch

### \*After Initialization you need to follow few steps to push your directory on github:

- Step 1: `git add .`
- Step 2: `git commit -m "Initial Commit"`
- Step 3: `git push -u origin main`
