[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15343653&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

Github is acloud based platform that allows or rather helps developers share, store and collaborate in coding.
some of the key functions of github include repository hosting,collaborative coding(code review,pull requests) and automation.
github aids collaborative software development by providing tools for code sharing,review and continuous intergration maing it easier for development teams to work together.

Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

github repository is a folder or rather a controlled storage for a code,documentation and project files.
A repository is created through the following steps;
-log in into your github account
-click on your profile pictuer in the upper right corner and select new repository on the drop down menu
-choose a name for your repository and maybe add an optional description of your repository.
-set visibility of the repository to be either public or private
-finish by clicking on create repository.

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

version control is a system that tracks changes  to files over time and in git in enables developers to keep track of their code bases as they work collaboratively.
Git hub  enhance version control for developers through the following ways;
-pull requests:developers can propose changes,discuss changes and work together in coding via request pulling.this promotes teamwork.
-Tranparency:developers can share their work with the world through public repositories.
Documentation:github incoporates readme files  and these provides files with project documentation

Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

Branches in github are independent lines of development within a repository. Branches are important because they allow one to work on code features without affecting the main branch,developers can create branches for specific tasks and merge them back through pull requests and incase of a mistake in a branch,it will not affect the main branch.
a branch can be created,changed and merged through the following ways;
-Open your repository on GitHub.
-Click on the Branch dropdown usually set to main or master.
-Type a new branch name and click Create branch.

-Switch to your newly created branch.
-Edit files, add new code, or make any necessary changes.
-Commit your changes with a descriptive message for example (add file x)

-Go back to the main branch
-Click on New pull request.
-Select your branch as the compare branch.
-Review the changes and discuss them if needed.
-Click Merge pull request to merge your changes into the main branch.


Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

A pull request is a mechanism for proposing changes to a repository.
Pull request  helps in development through creation of pull requests where developers can review code,collaboration where developers can share knowledge and merging where changes are merged into the target branch.

-Create a new branch for your changes.
-Commit Changes:Make your code changes within the branch.Commit your changes.
-Push to Remote:Push your branch to the remote repository on GitHub.
-Create Pull request:Go to the repository on GitHub.
-Click New pull request.
-Select your branch as the compare branch.
-Click Create pull request.

-Review Changes:Open the Pull request.Examine the code changes, comments, and files.
-Leave Comments:Add comments directly on the code.
-Suggest improvements, ask questions, or provide feedback.
-Approve or Request Changes:If satisfied, approve the Pull request.
If changes are needed, request them.
-Merge Pull request:Once approved, click Merge pull request.
-Choose merge options (e.g., squash commits or preserve history).


GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

Github actions is a continuous intergration and continuous delivery platform that aoutomates your software development workflows.
Github actions are used in the foliwing ways;
-Create workflows that build, test, and deploy your code.
-Automate tasks from idea to production right within your GitHub repository.
-CI: Run tests whenever you push changes to your repository.
-CD: Deploy merged pull requests to production.

-In your GitHub repository, create a .github/workflows directory.
-Inside this directory, add a YAML file with your workfslow configuration.
-Define the steps necessary for building, testing, and deploying your code
-Customize the steps according to your project’s needs.
-If your workflow requires secrets such as API keys, credentials, set them up in your repository settings.
Reference these secrets in your workflow file.
-Push your changes to the repository.


Introduction to Visual Studio:

What is visual studio and what are some of its key features. How does it differ from Visual Studio Code?

Visual Studio is a powerful integrated development environment (IDE) developed by Microsoft.It serves as a comprehensive tool for writing, editing, debugging, and building code.
Key features of visual studio include code edditing and debugging,language support,designing tools CI/CD intergration and plug ins and extensions.

Visual studio and visual studio code differ in several aspects such as size,extensions and operating sysytem specifications.
For instance, visual studio can only run on windows and mac whereas visual studio code can run on windows, mac and linux.
On the aspect of space, visual studio occupys 62gb on windows and 4.2 gb on mac whereas visual studio code occupys minimal space on all operating systems.
For the extensions,visual studio come with debuggers and editorsand compilers. On the other hand, on visual studio code, one has to install numerous debbugers and compilers to ensure smooth coding and most of these extensions are not made by microsoft but they are approved by microsoft. 

Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

Open visual studio and authenticate if it is  connected to git hub as this allows one to create repositories  and push them directly.
-search for repositories in github.
-Clone a repository to your local machine
-Start commiting and pushing code changes.
-Push new repos to github directly from visual studio.
-Switch between branches  to view chsnges and make commits
-meRge branches with IDE
-Create pull requests from remote branches
Visual studio will detect merge conflicts and use the editor to resolve conflicts.

Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

Visual studio provides several debbiging tools  that help identify and fix issues in a code.
Breakpoints-set breakpoints at specific lines of code  to pause executiion and inspect variables and othe relevant information during runtime
Step over-skips over function calls and move to the next line of code without diving into details of the called function.
Restart quickly-quickly restart your application without rebuilding it.

Developers can utilize debbuging tools to identify and fix issues in their code.
For instance, they can  set breakpoints at specific lines of code to pause execution and inspect variables and other relevant information.
They can use restart quickly to instatly restart their application without rebuilding.
They can also use run to cursor to execute code until it reaches the cursor position allowing them tskip unnecessary steps.

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

Visual studio and github have been intergrated to work together in development beacause now one can create repos,push cimmits and manage a code withpiu leaving  the IDE
The two have been intergrated such that visual studio alows  you to create a pull request fro remote branches. 
One can also merge or rebase branches directly from visual studio after completeing features.


Project: “EcoTrack” – Wildlife Conservation App

Description: EcoTrack is an open-source mobile app aimed at promoting wildlife conservation. Users can report wildlife sightings, track endangered species, and contribute to research efforts.
Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
