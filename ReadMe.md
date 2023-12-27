Overview
In this workshop, you will practice using git to version control your projects.
Repo Setup
For this section, you will need VS Code and GithubLinks to an external site..

Create a  block04 folder.
Open the folder in VS Code. Make sure you did not accidentally open a parent folder instead such as coursework or unit01.
Create a ReadMe.md file in the folder.
In the ReadMe.md file, paste the instructions from this workshop.
Switch to the Source Control panel and select Publish to GitHub.
Verify that your repository was successfully published by checking your GitHub account.
On your published repository page, click the Settings button, and then on the left sidebar, navigate to the Collaborators page.
Click the Add people button and add your instructor. You can do so via their Github username.
Stage and Commit
Create an index.html file and add the starting html template.
In your readme.md file, replace the text with the name of your favorite book or movie.
Add a header in the html file that says "Summary" and a short paragraph below that includes a 1-2 sentence summary.
Make sure all your changes are saved before staging and committing them. 
Your commit message should use the following format feat: add book summary
Push and pull your changes and verify that they went through by checking your GitHub repo online.
 

Feature Branches
When developers work on a project, especially if they are working with others, they do not work directly on the main branch. Instead, they work on separate feature branches.

Creating a Local Feature Branch
Create a branch named refactor/#1-refactor-summary-to-key_points.
In your html file, remove the summary header and the summary paragraph
Make sure all your changes are saved before staging and committing them. 
Your commit message should use the following format feat: remove book summary.
Push and pull your changes and verify that they went through by checking your GitHub repo online.
Add a key points header and list a few main events in the book where the summary header used to be.
Make sure all your changes are saved before staging and committing them. 
Your commit message should use the following format feat: add book key points
Push and pull your changes and verify that they went through by checking your GitHub repo online.
Merge your branch to the main branch by selecting the Compare and Pull Request button on GitHub.
Note: using descriptive branch names will help you stay organized!

Note: It is best practice to keep each commit to one discrete change when possible. You can never have too many commits!

Submission
Submit a link to your GitHub repository. It should have:

README.md and index.html file.
The updated index.html is in the key_points branch. 
Recap
That's it! You're done! Whenever you work on a project, follow these steps:

Clone down the repo (if it has already been created )to your local machine.
Create a local feature branch
Stage and Commit changes.
Once you're done with your feature branch, merge it into your main branch.