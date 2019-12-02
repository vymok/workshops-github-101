# Welcome to the Git 101 workshop! 



## Intro & Cheatsheets

Here are some useful cheatsheets for Git & GitHub commands:

- Cheatsheet for [Mac & Linux Users](https://www.slideshare.net/paalringstad/command-cheatsheets-mac)
- Cheatsheet for [Windows Users](https://www.slideshare.net/paalringstad/command-cheatsheets-windows-138186563)
- List of [Git Commands](https://github.com/joshnh/Git-Commands)


# Before you start
1. In your terminal, run the command `git version`. If Git is not installed, you can [install it here](https://git-scm.com/downloads)
2. For some parts of the challenge, we will be using a text editor. Download [Sublime Text if you don't have one already](https://www.sublimetext.com/3)
3. Set your username & email on git. To set your username, run: `git config --global user.name "your_name"`. Switch your_name for whatever your name is. 
4. To set your email, run: `git config --global user.email "your_email"`. Switch your_email to whatever your email is. 
5. Make sure to sign up for GitHub. 


# Challenge 1
Remember to use your cheatsheet, get help from your buddy, & ask for help. 

1. Open your terminal
2. Print out your directory
3. Create a new folder using your command line 
4. Move into your new folder and create a new file named `index.html`
5. Initialise git for the directory 
6. On your desktop, drag your new `index.html` file into your text editor. Write something inside & save it. 
7. In your terminal, which Git command do you use to review what changed in your file? Use it. 
8. Add a commit message to explain what changed in your file. 
9 Create a new branch! 
10. Jump into your new branch. 
11. Now, use `git checkout` to get back to your master branch. 


# Challenge 2

1. Open your terminal
2. Print out your current directory. Make sure you are in your Desktop. 
3. Go to this repo: `https://github.com/sheesh19/workshops-github-101`
4. **Fork** the repository (to make you the Master of the repo). 
5. `git clone` your new repo into your folder. 

# Challenge 3 
1. Create a new branch & switch to the new branch. 
2. Update the HTML file with your name & save it. 
3. To save the version, use `git add <file_name>`. 
4. Add a commit message with `git commit -m "your commit message"`.
5. Run `git remote -v` to see the remote repo linked to your project. 
6. Finally, push your branch to GitHub! Make sure to use `git push origin <your_branch_name>`.
7. Create a pull request & merge your branch on GitHub. 



**Congratulations!** You've made your own local files, used a GitHub repo, and created a pull request to update the master. 


- For more [Windows Terminal Commands](https://www.thomas-krenn.com/en/wiki/Cmd_commands_under_Windows)
- For more [Mac & Linux Terminal Commands](https://fossbytes.com/a-z-list-linux-command-line-reference/)
