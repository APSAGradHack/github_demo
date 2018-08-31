# APSA Hackathon GitHub Demo

## Outline
1. What is GitHub?
2. The Basics: Cloning, branching, committing, pushing
3. Making a GitHub Site
4. More Resources

# Useful links
## [This demo page](https://github.com/APSAGradHack/github_demo)
* If you are on the Hackathon team making the GitHub site, [sign up here](https://goo.gl/forms/pVIR1Mb6rMYdllOg2)
* [GitHub Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

# What is GitHub?
Git (minus the "hub") is a "version control system" - software designed to let people collaborate on the same body of code and keep track of how each file in the project was edited over time. GitHub is a website that displays these projects (called "Repositories") and their edit histories (called "Commits") and allows users to contribute to projects or adapt existing code for new projects.

This is very useful for projects where many people edit the same content at the same time and it also gives you a full history of all changes, so you can go back to an old version of your code if something goes wrong.

# The Basics
Throughout this tutorial, we'll be using the APSA Hackathon GitHub website as an example, but you can follow these instructions for any repository (or create a new repository for your own project!).

### Make a github account
Head to [GitHub's website](https://github.com/) and create an account.

### Download GitHub Desktop.
Go to [desktop.github.com](https://desktop.github.com/) to download and install GitHub Desktop. This is what we will use to track and push our changes back up to GitHub's website. You can also do everything we're going to learn today using the command line, but we won't be covering that.

## The basic workflow
We will create a "branch" of the main project, make our changes, and then merge them into the master project. This lets us all work on the code simultaneously and avoid creating errors in the main website or overwriting each other by accident.
![alt text][branching_chart]

## How to use GitHub
### Clone a repo
First, clone the repository you'd like to work on:
1. Go to the repository on GitHub's website to see what it looks like: [https://github.com/APSAGradHack/APSAGradHack.github.io](https://github.com/APSAGradHack/APSAGradHack.github.io).
* In GitHub Desktop go to File > Clone repository and paste the repository URL above where prompted.

![alt text][clone_repo]

2. All of the files in the repository will now also exist locally on your computer.

### Make a new branch
Since many people will be working on this site at once, you want to create a new branch or version of the code so that people aren't editing the exact same code at once.

3. Go to the dropdown menu that says "Current branch: master" in GitHub desktop, click, and make a new branch with your name in it (i.e. meg_working). Don't use spaces or other punctuation!
![alt text][create_branch]

### Make changes
4. Open the local files that were created when you cloned the repository and edit whatever you want to in your favorite text editor! Save your changes!

### Commit changes
5. Go back to GitHub Desktop. You should now see some content in the main window. The lines of each file highlighted green are lines you added or changed. The red highlighted lines are deletions.

![alt text][change_log]

---

6. These changes don't exist online yet, so nobody else can see them. To push the changes back up so others can share in them, you need to "commit" the changes. Every time you commit, GitHub takes a snapshot of the project along with your comment about what you changed.
 
7. Go to the box in the bottom left of GitHub desktop and write a summary of the changes you've made (you can be more verbose in the description box as well if you want), before clicking "Commit to [BRANCH]". 

![alt text][commit_message]

---

8. Then click "Publish Branch" if you haven't committed anything from the branch before. If have already pushed a commit on this branch, the button will say "Push Origin" instead but it does the same thing. Now your changes will be on the GitHub website in your branch.

9. Now you want to get the changes in your branch into the "master" branch so everyone can see and use them. Go to the repository on the GitHub website and you will see a green button that says "Compare & pull request"

![alt text][pull_req_1]

---

10. Make sure there aren't any conflicts and then follow through with the commit, adding any commentary you want. Now your changes will be in the "master" branch!
![alt text][pull_req_2]

11. Now that your changes are in master, you can delete your branch locally and on the GitHub website. If you want to make more changes, just start over with a new branch!
![alt text][delete_branch]

---

# Making a Github Site
GitHub also lets users host websites using GitHub Markdown files to create pages. This is great for static websites that don't require users to interact with the site much, such as personal websites.

## What is GitHub markdown?
Markdown is just a formatting style. GitHub Markdown is very similar to RMarkdown and easy to use. The page you are reading right now is written in GitHub markdown. All markdown files are saved as `.md` file extensions.

For example, to create a header followed by a list, one would write:
``` # This is a big header
### This is a smaller header
1. Here
2. Is an
3. Ordered list

* this list
* is unordered
```
Which shows up in markdown and on the GitHub site as:
# This is a big header
### This is a smaller header
1. Here
2. Is an
3. Ordered list

* this list
* is unordered

A helpful GitHub Markdown cheat sheet is [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
---

# Our website
After this demo one of the hackathon teams will be working on this website:
* [The website can be viewed here](https://apsagradhack.github.io/)
* [And the sourcecode is here](https://github.com/APSAGradHack/APSAGradHack.github.io)

To edit the website, follow the directions for GitHub above to clone the repository, make and push changes, and submit pull requests. 

# Helpful Links
* [Signup form for the team making the GitHub site](https://goo.gl/forms/pVIR1Mb6rMYdllOg2)
* [GitHub Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [APSAGradHack GitHub org](https://github.com/APSAGradHack/)

![alt text][git_comic]
_From [xkcd](https://xkcd.com/1597/)_


[clone_repo]: https://github.com/APSAGradHack/github_demo/blob/master/pics/clone_repo.png "Clone repo screenshot"
[create_branch]: https://github.com/APSAGradHack/github_demo/blob/master/pics/create_branch.png "Create branch screenshot"
[change_log]: https://github.com/APSAGradHack/github_demo/blob/master/pics/change_log.png "Change log on GitHub Desktop" 
[commit_message]: https://github.com/APSAGradHack/github_demo/blob/master/pics/commit_message.png "Commit message on GitHub Desktop" 
[pull_req_1]: https://github.com/APSAGradHack/github_demo/blob/master/pics/pull_req_1.png "Pull request button" 
[pull_req_2]: https://github.com/APSAGradHack/github_demo/blob/master/pics/pull_req_2.png "Pull request form" 
[pull_req_3]: https://github.com/APSAGradHack/github_demo/blob/master/pics/pull_req_3.png "Pull request form 2" 
[delete_branch]: https://github.com/APSAGradHack/github_demo/blob/master/pics/pull_req_1.png "Delete branch" 
[git_comic]: https://github.com/APSAGradHack/github_demo/blob/master/pics/git_xkcd.png "Git comic"
[branching_chart]: https://github.com/APSAGradHack/github_demo/blob/master/pics/branching_chart.png "Git comic"

