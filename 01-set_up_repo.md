# Set up your repository on GitHub


## Step 1: Sign up for GitHub

You will need a GitHub account.

It's easy and free to [sign up](https://github.com/join).


## Step 2: Sign in to GitHub

Make sure that you are [signed in](https://github.com/login) to GitHub.


## Step 3: Fork this repository

Click the **Fork** button at the upper right hand corner of the page:

![fork](img/forking_repo.png)

This makes a personal copy of the repository. Your forked copies will show up in your *Repositories* section.

This repository is `thisismetis/dsp`. Your forked copy will be `your_github_user_name/dsp`.

## Step 4: Clone the repository locally

This makes a copy of the repository in your laptop. Click on the clipboard image on the right sidebar to copy the HTTPS clone URL. 

Include instructions for caching or too much??

![edit](img/clone_repo.png)

Go to your terminal and navigate to whichever folder you will be using to save the pre-work. Type `git clone` and then paste the clone URL.  

`git clone https://github.com/your_username/dsp.git`  

Navigate to the repository. Your terminal window should now show show something like this:

` dsp git:(master) `

## Step 5: Start committing

Now you can complete the challenges in your text editor and then `push` them up to GitHub when you're done. We will **not** be doing any branching, merging, rebasing or any of that fun stuff (yet).  

There's some important terminology to consider for this part before we move on.  

There's three main states that your files can reside in: 

_Modified_ means that there's been changes to the file but it's not committed yet. 

_Committed_ means that the data is stored locally.

_Staged_ means that you have marked a file to go into your next commit snapshot.

The **staging** area 

There's three basic commands you need to learn for this part:

`git add filename`  
This command will add any changes you just made to the "staging" area. This is ba

`git commit -m "I just did some cool stuff`  
`git push`  


<!-- 


## Step 4: Edit your fork

There are files in your forked repository that you need to edit to add your work.

When viewing an individual file in your forked repository on GitHub, you will an see "Edit this file" button that you can click to get an in-browser editor.

![edit](img/edit_file.png)

After you've edited the file, you need to _commit_ your changes to make them permanent. At the bottom of the page you can add a _commit message_ describing your changes and then click the green "Commit changes" button.

![commit](img/commit_file.png)

You can repeat the edit and commit process as many times as you like. You don't have to be totally done with a file to commit. Commit incrementally!

Here's your first chance to practice this:



What is your favorite [emoji](http://www.emoji-cheat-sheet.com/)?

>> REPLACE THIS TEXT WITH YOUR RESPONSE




### Deepen your knowledge

The process above is designed to be accessible to anyone regardless of background. There is much more to learn about `git` and GitHub.

To get a complete understanding of `git`, you should read [Pro Git](http://git-scm.com/book/en/v2). It's available free online or as a printed book.

[<img src="img/pro_git.png" title="Pro Git" width="250" />](http://git-scm.com/book/en/v2)

It isn't required, but you can also submit work to your forked repository by `clone`ing your fork, editing files on your machine, `add`ing them to the staging area, `commit`ting them, and `push`ing your changes back up to GitHub.
