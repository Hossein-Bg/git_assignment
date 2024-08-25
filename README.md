# Git Assignment - Hossein-Bg
----------------------------------------

a. What is an issue?
Issues are used to track tasks, enhancements, bugs, feature requests, and more.
For more info please check the issues section on the repo.

----------------------------------------

b. What is a pull request?
PR serves as a proposal to merge changes made in one branch of a repository into another, typically from a feature branch into the main branch.

----------------------------------------

c. Describe the steps to open a pull request?
1. Fork the Repository
This create a copy of the repository under your GitHub account similar to how we did it for the shell assignment.
2. Use the git clone https://github.com/your-username/repository-name.command to clone the repository.
3. Create a new branch with git checkout -b 'Branch name' command.
4. Make the necessary changes to the code or documentation in your new branch.
5. Push the branch to your GitHub repository.
6. Open a Pull Request by going to the repository page on GitHub where you pushed your branch. You will see a banner with a Compare & pull request button. Click on it, or go to the Pull requests tab and click New pull request.
7. Fill Out the Pull Request Form and submit the pull request.

----------------------------------------

d. Describe the steps to add a collaborator to a repository (share write permissions)
1. Sign in to your GitHub account, then navigate to the git-assignment repo.
2. Open the repo and click the Setting tab, which is located at the top of the page.
3. In the left sidebar, under Access, click on Collaborators to open the collaborators management page. (you have to enter your GitHub pass to enter to the collaborators management page)
4. Click the Add people and enter the GitHub Username, Full name or email address of the person you want to add as a collaborator, then click the add button. (Here I added Simeon as a collaborator for my git-assignment but I am not sure if he will accept my invitation or not.) 
5. After accepting the invitation, your collaborators can push changes to the reop.

----------------------------------------

e. What is the difference between git and GitHub?

Git is a version control system that allows programmers or developers to manage and keep track of changes in their code. On the other hand, GitHub is a cloud-based hosting service that lets you manage Git repositories.

----------------------------------------

f. What does git diff do?

The git diff command helps to see, compare, and understand changes in your project. It compares changes between commits, branches, or the working directory and the staging area. Running git diff without any parameters will show you all of your changes since you last commited.
It can come with different parameters such as:
* git diff "certain file" --> You will see only the changes in a certain file.
* git diff --staged "certain file" --> By adding the --staged option, Git will show which local changes you have already added to Staging Area via "git add", and so on.

----------------------------------------

g. What is the main branch?

The main branch in Git is the default branch. When anyone visits your repo and forks or clones it, that is the branch that gets checked out and served down locally to their machine. Besides, The main branch is the most up to date version of the project. This branch was often called master, but many projects use main as the default name for this branch.

----------------------------------------

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

Usually we shouldn't push changes directly to the main branch after initial commit. It is best to use branching strategy instead. 
Additionally, the main branch should always contain stable code. Besides, it's important for changes to be reviewed by other team members before they are merged into the main branch. This ensures that the code meets quality standards and aligns with the project's goals. Another reason is that, by using separate branches, you can run tests on your code changes and once you are sure that the code passes all tests you can merge it safely into the main branch.