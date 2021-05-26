# GitHub Install & Tutorial

## What is Git and GitHub?

### Git

Git is an open-source version control system. Basically a way of easily saving progress on a project and tracking what's been done.
Git is a command-line tool, favoured by the majority of developers to keep track of their projects due to its many advantages.

![Git Logo](images/git-logo.png)

### Github

Now that you've learnt what git is, time to learn what it all revolves around, Github.
Github is a central repository to store your projects and have several other developers collaborate on it together. Simply, Github will look after our code, then let other people copy it down without changing the code we've saved ourselves (unless you want to).
![Github Logo](images/github-logo.png)
In this course we're going to be using a tool called "Github Desktop", a user friendly program that will let you use git and github without needing to touch the command line.

## Install Tutorial

### Sign up to Github

Open a browser:

1. Navigate to https://github.com
2. Enter a unique username, your email address and a memorable password.
3. Verify that you're not a robot
4. Click "Create Account"
5. Your Github account setup is now complete.

### Windows

Open a browser:

1. Visit desktop.github.com.
2. Click Download for WIndows (64bit).
3. When prompted, click Run.
4. Allow the installation to download and install.
5. Once the installation completes, GitHub Desktop will launch.

### Mac

Open a browser:

1. Visit desktop.github.com.
2. Click Download for macOS.
3. In your computer's Downloads folder, double-click the GitHub Desktop zip file.
4. After the file has been unzipped, double-click GitHub Desktop
5. Once the installation completes, GitHub Desktop will launch.

## First Repository

The goal of this tutorial is to teach you:

- how to make your first repository (sometimes refered to as a repo),
- clone it to your local computer,
- make a change,
- push it back up to github.

1. Once logged in, click the green "New" button on the left side of the screen.
2. Give a name to this repository and be sure to check the box titled "Add a README file".
   This will ensure that you can easily clone down the repository.
3. Click "Create Repository".  
   Your repository is now created, and can be changed however you want.
   Everything saved here is backed up on Github, safe if you accidentally delete it on your personal computer.  
   Scroll down the page and you should see the title of your repository, our goal is to change this.
4. Click the green "Code" button and take a look at the dropdown. Copy the link that is shown and head back to Github Desktop.
5. Under file, choose "Clone Repository" and go to the URL tab. Paste in the link you copied, choose where you want to save your repository, and finally click clone.
6. Open your Text Editor and open the file that you just cloned down.  
   Everything you change here will only be changed on your local copy, until you push it back up.
7. Open the only file in the folder, called README.md. This file is typically used to describe the project, any instructions to make it run, etc. In this tutorial we're just going to change it a little.
8. In README.md, delete everything (should only be one line), and write your name inside. Then make sure to save it.
9. Once the README.md file has been saved, once again go back to Github Desktop and you'll be shown what's been removed and added to the file. Make sure you're happy, because nothing has been saved on Github yet.
10. When you're happy, go to the bottom left of Github Desktop and click on the text bar that says "Update README.md". Type in "Wrote my name".  
    This line is a quick description of the commit, or a summary of what's been changed.  
    Click the blue "Commit to Main" button, then the "Push Origin" button on the top of the program.
11. Enter your Username and Password to sign in, then submit them. Your changes have now been pushed to Github. Go to Github in your browser and refresh the page. The title on the bottom of your page should have now changed to your name.

You've now created a repository, cloned it down, made a change, committed that change and pushed it back up to Github.
