# APSA Hackathon GitHub Demo

## Outline
1. What is GitHub?
2. The Basics: Cloning, branching, committing, pushing
3. Making a GitHub Site
4. More Resources

## What is GitHub?
Git (minus the "hub") is a "version control system" - software designed to let people collaborate on the same body of code and keep track of how each file in the project was edited over time. GitHub is a website that displays these projects (called "Repositories") and their edit histories (called "Commits") and allows users to contribute to projects or adapt existing code for new projects.

This is very useful for projects where many people edit the same content at the same time and it also gives you a full history of all changes, so you can go back to an old version of your code if something goes wrong.

## The Basics
Throughout this tutorial, we'll be using the APSA Hackathon GitHub website as an example, but you can follow these instructions for any repository (or create a new repository for your own project!).

#### Make a github account
Head to [GitHub's website](https://github.com/) and create an account.

#### Download GitHub Desktop.
Go to [desktop.github.com](https://desktop.github.com/) to download and install GitHub Desktop. This is what we will use to track and push our changes back up to GitHub's website. You can also do everything we're going to learn today using the command line, but we won't be covering that.

### How to use GitHub
#### Clone a repo
First, clone the repository you'd like to work on:
* Go to the repository on GitHub's website to see what it looks like: [https://github.com/APSAGradHack/APSAGradHack.github.io](https://github.com/APSAGradHack/APSAGradHack.github.io).
* In GitHub Desktop go to File > Clone repository and paste the repository URL above where prompted.

![alt text][clone_repo]

* All of the files in the repository will now also exist locally on your computer.

#### Make a new branch
Since many people will be working on this site at once, you want to create a new branch or version of the code so that people aren't editing the exact same code at once.

* Go to the dropdown menu that says "Current branch: master" in GitHub desktop, click, and make a new branch with your name in it (i.e. meg_working). Don't use spaces or other punctuation!
![alt text][create_branch]

#### Make changes
* Open the local files that were created when you cloned the repository and edit whatever you want to in your favorite text editor! Save your changes!

#### Commit changes
* Go back to GitHub Desktop. You should now see some content in the main window. The lines of each file highlighted green are lines you added or changed. The red highlighted lines are deletions.

![alt text][change_log]

* These changes don't exist online yet, so nobody else can see them. To push the changes back up so others can share in them, you need to "commit" the changes. Every time you commit, GitHub takes a snapshot of the project along with your comment about what you changed.
 
* Go to the box in the bottom left of GitHub desktop and write a summary of the changes you've made (you can be more verbose in the description box as well if you want), before clicking "Commit to [BRANCH]". 
![alt text][commit_message]


* Then click "Publish Branch" if you haven't committed anything from the branch before. If have already pushed a commit on this branch, the button will say "Push Origin" instead but it does the same thing. Now your changes will be on the GitHub website in your branch.

* Now you want to get the changes in your branch into the "master" branch so everyone can see and use them. Go to the repository on the GitHub website and you will see a green button that says "Compare & pull request"

![alt text][pull_req_1]

* Make sure there aren't any conflicts and then follow through with the commit, adding any commentary you want. Now your changes will be in the "master" branch!
![alt text][pull_req_2]

![alt text][pull_req_3]

* Now that your changes are in master, you can delete your branch locally and on the GitHub website. If you want to make more changes, just start over with a new branch!
![alt text][delete_branch]

## Making a Github Site

## More Resources


[clone_repo]: https://github.com/APSAGradHack/github_demo/pics/clone_repo.png "Clone repo screenshot"
[create_branch]: https://github.com/APSAGradHack/github_demo/pics/create_branch.png "Create branch screenshot"
[change_log]: https://github.com/APSAGradHack/github_demo/pics/change_log.png "Change log on GitHub Desktop" 
[commit_message]: https://github.com/APSAGradHack/github_demo/pics/commit_message.png "Commit message on GitHub Desktop" 
[pull_req_1]: https://github.com/APSAGradHack/github_demo/pics/pull_req_1.png "Pull request button" 
[pull_req_2]: https://github.com/APSAGradHack/github_demo/pics/pull_req_2.png "Pull request form" 
[pull_req_3]: https://github.com/APSAGradHack/github_demo/pics/pull_req_3.png "Pull request form 2" 
[delete_branch]: https://github.com/APSAGradHack/github_demo/pics/pull_req_1.png "Delete branch" 

