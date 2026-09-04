My Static Website
Task 5 - Deploy a Static Website Using GitHub Pages

This project demonstrates how to create and deploy a simple static website using Git, GitHub, and GitHub Pages.

Objective

The objective of this task is to understand version control, static website hosting, and the deployment workflow using GitHub Pages.

Technologies Used
HTML
CSS
JavaScript
Git
GitHub
GitHub Pages
Visual Studio Code
Features
Simple portfolio website
Responsive design
HTML structure
CSS styling
JavaScript interaction
Free hosting using GitHub Pages
Project Files
index.html - Contains the structure and content of the website.
style.css - Contains the styling and design of the website.
script.js - Contains the JavaScript functionality.
README.md - Contains project documentation and interview questions and answers.
Deployment

This website is deployed using GitHub Pages from the main branch and the root folder.

Live Website

https://mdbilalahmed2005.github.io/

GitHub Repository

https://github.com/MDBilalAhmed2005/MDBilalAhmed2005.github.io

Interview Questions and Answers
1. What is Git and why use it?

Git is a distributed version control system used to track changes in files and source code. It helps developers manage different versions of a project, maintain a history of changes, work on different branches, and collaborate with other developers.

2. How do you push code to GitHub?

To push code to GitHub, we first add the project files, create a commit, connect the local repository to the GitHub repository, and then push the changes.

Common commands are:

git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repository-url>
git push -u origin main


After the first push, we can use:

git add .
git commit -m "Update website"
git push

3. What is GitHub Pages?

GitHub Pages is a free hosting service provided by GitHub. It allows users to host static websites directly from a GitHub repository.

In this project, the website files are stored in the GitHub repository and GitHub Pages publishes the website online.

4. What is the difference between static and dynamic websites?

A static website contains predefined files such as HTML, CSS, and JavaScript. The content is generally fixed and is delivered to visitors as stored.

A dynamic website can generate or update content based on user actions, databases, APIs, or server-side programming.

Examples:

Static website: Portfolio website, documentation website, simple landing page.
Dynamic website: Online shopping website, social media website, banking application.
5. How do you revert commits in Git?

The git revert command is used to undo the changes introduced by a previous commit while keeping the Git history.

Example:

git revert <commit-id>


This creates a new commit that reverses the changes made by the selected commit.

6. What is branching in Git?

Branching allows developers to create separate lines of development in a Git repository.

It allows developers to work on new features or bug fixes without directly changing the main branch.

Example:

git branch feature
git checkout feature


After completing the work, the feature branch can be merged into the main branch.

7. Explain pull requests.

A pull request is a request to merge changes from one branch into another branch on GitHub.

Pull requests allow developers to:

Review code changes.
Discuss changes with other developers.
Find and fix problems.
Run tests before merging.
Approve changes before they are merged.
8. How do you resolve merge conflicts?

A merge conflict occurs when Git cannot automatically combine changes from different branches.

To resolve a merge conflict:

Open the file containing the conflict.
Identify the conflicting sections.
Decide which changes should be kept.
Remove the conflict markers.
Save the file.
Add the resolved file.
Commit the changes.

Example:

git add .
git commit -m "Resolve merge conflict"

9. How can you host a website for free?

A static website can be hosted for free using GitHub Pages.

The basic process is:

Create a GitHub repository.
Add the website files such as HTML, CSS, and JavaScript.
Push the files to GitHub.
Enable GitHub Pages in repository settings.
Select the main branch and / (root) folder.
GitHub publishes the website using a GitHub Pages URL.

For this project, the live website is:

https://mdbilalahmed2005.github.io/

10. What is continuous deployment?

Continuous deployment is a software development practice where code changes are automatically deployed to a live environment after passing the required checks.

For example, when changes are pushed to a configured GitHub branch, an automated deployment process can build and publish the latest version of the website.

GitHub Pages can automatically deploy updated website files after changes are pushed to the configured publishing branch.

Key Concepts
Git
GitHub
GitHub Pages
Version Control
Git Branching
Git Commits
Git Push
Pull Requests
Merge Conflicts
Static Hosting
Continuous Deployment
Conclusion

This task helped me understand how to create a static website, manage the project using Git, upload the project to GitHub, and deploy the website using GitHub Pages.
