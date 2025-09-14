# 21_GitHub_OpenSourceChallenge
OpenSource Challenge a 21 Day immersive Experience.
## Day1- Challenge
This is the First Day of learning a few basic concepts of GitHub and I would like to share them here probably the basics like dashboard, profiles, repositories, pull Requests, and along with that the concept of repository and how a few Markdowns are being done in a GitHub repository and why do we use them if needed !!
## What and Why is GitHub used for?
GitHub is generally used in making work simple for people who wants to collaborate and it eases work load for people who are far away and wanted a connecting platform helping us in showing every commit that we pull in a detailed manner and this is what makes it different from other platforms. And that is a collaborative software development which is built upon Git version control System. And here I would like to highlight its Key uses and Benefits such as:
### Version Control and Code Hosting
### Collaboration and Teamwork
### Code Review and Quality Assurance
### Project Managemen
### Open-Source Development
### Community and Networking
### Accessibility and Portability
and all this code is beign stored in a repository 
## Repository 
a place where are the files are being stored and shows what a project contains and probably every detail of it. And version control which means it has a track of everything which helps us know who had given a new approach or who made the changes neccessary and every move is being noted.
## Issues:
A system for tracking tasks, bugs, and enhancements within a project, allowing for discussion, assignment, and linking to code changes.
## Pull Requests (PRs):
A mechanism for proposing changes from one branch to another, facilitating code review, discussion, and collaborative integration of new features or bug fixes.
## Branches and Commits:
Within a repository, development can occur on different "branches" to isolate changes. "Commits" are snapshots of the repository at specific points in time, recording the changes made.
## Before starting with these repositories We have to learn what are the terms that makes the repository.
#### Branch -	A parallel version of your code that is contained within the repository, but does not affect the primary or main branch.
#### Clone -	To download a full copy of a repository's data from GitHub.com, including all versions of every file and folder.
#### Fork -	A new repository that shares code and visibility settings with the original "upstream" repository.
#### Merge -	To take the changes from one branch and apply them to another.
#### Pull request -	A request to merge changes from one branch into another.
#### Remote -	A repository stored on GitHub, not on your computer.
#### Upstream -	The branch on an original repository that has been forked or cloned. The corresponding branch on the cloned or forked repository is called the "downstream."

## Day2 Challenge
Welcome to the world of Git! Think of Git as a powerful time machine for your code. It keeps track of every change you make, so you can always go back to a previous version if you need to.

1. git init
This is your starting point. It's the command you use to turn a regular folder on your computer into a Git-managed project, also known as a repository. You only run this command once per project.

Analogy: This is like creating a brand new notebook for a project.

How to use:

git init
<img width="1023" height="608" alt="Screenshot 2025-09-12 173727" src="https://github.com/user-attachments/assets/cbf24a3b-31b3-4162-babe-ee8e7baf6cb3" />

2. git add <file_name>
This command "stages" a file for a commit. Think of the staging area as a preparation space. When you're ready to save a snapshot of your work, you first select the files you want to include using git add.

Analogy: This is like picking which pages in your notebook you want to include in your next chapter summary.

How to use:

# To stage a specific file
git add index.html

# To stage all changes (new and modified files)
git add .

3. git commit -m "<message>"
This is the command that saves your staged changes as a new snapshot in your project's history. Every commit must have a descriptive message that explains what you changed. This message is super important for you and others to understand your project's history.

Analogy: This is like writing a new chapter in your notebook. The message is the title of the chapter.

How to use:

git commit -m "Add new homepage layout"
<img width="685" height="440" alt="Screenshot 2025-09-12 173136" src="https://github.com/user-attachments/assets/00921d19-63bb-4119-8bec-71dff9199fab" />

4. git status
This is your most-used command! It shows you the current state of your project. You can use it at any time to see which files you've changed, which ones are staged, and which ones are ready to be committed.

Analogy: This is like a table of contents that updates in real-time. It tells you exactly where you are in your project.

How to use:

git status
<img width="1459" height="1104" alt="Screenshot 2025-09-12 174116" src="https://github.com/user-attachments/assets/c6623d56-b9cd-4510-bc21-a42220fc6beb" />

5. git push
Once you've made some commits on your local machine, this command "pushes" those commits to a remote repository, like the one on GitHub. This is how you share your work with others or back it up online.

Analogy: This is like uploading your notebook to the cloud.

How to use:

git push

6. git clone <url>
This is how you get a copy of an existing project from a remote repository, like GitHub, to your local machine. You only need to do this once per project.

Analogy: This is like downloading a copy of a friend's notebook to read and work on yourself.
<img width="1230" height="894" alt="Screenshot 2025-09-12 174824" src="https://github.com/user-attachments/assets/a45d9299-6eff-4833-ada6-1734eaff428c" />
And this is what I have learnt in Git in Day2.

How to use:

git clone [https://github.com/your-username/your-repo.git](https://github.com/your-username/your-repo.git)
