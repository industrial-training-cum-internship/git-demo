## Git Tutorial for Internship

### Introduction to Git

Git is a version control system that allows you to track changes in your codebase. It helps you collaborate with others, manage different versions of your code, and easily revert to previous states if needed.

#### Installation

1. Download Git: Visit the official Git website (https://git-scm.com/) and download the appropriate installer for your operating system.
2. Install Git: Run the installer and follow the installation instructions. Make sure to choose the appropriate settings based on your preferences.

### Setting Up Git

Once you have Git installed, follow these steps to set it up:

1. Configure user details: Open a terminal (Command Prompt, Git Bash, or Terminal) and enter the following commands, replacing `YOUR_NAME` and `YOUR_EMAIL` with your name and email address:
   ```
   git config --global user.name "YOUR_NAME"
   git config --global user.email "YOUR_EMAIL"
   ```

2. Verify configuration: To verify your configuration, run the following command:
   ```
   git config --global --list
   ```

   This command will display your Git configuration details.

### Git Basics

#### Creating a New Repository

To create a new Git repository, follow these steps:

1. Create a new directory: Open a terminal and navigate to the desired location for your repository. Use the following command to create a new directory:
   ```
   mkdir my-repo
   ```

2. Initialize Git repository: Navigate into the newly created directory using `cd my-repo`, then run the following command to initialize the Git repository:
   ```
   git init
   ```

#### Basic Workflow

1. Adding files: Place your project files inside the Git repository directory. Use the following command to stage files for committing:
   ```
   git add file1 file2 ...
   ```

2. Committing changes: To commit the staged changes, use the following command:
   ```
   git commit -m "Commit message"
   ```

   Replace `"Commit message"` with a brief description of the changes you made.

3. Checking repository status: You can check the status of your repository using the following command:
   ```
   git status
   ```

   This command shows the current branch, any modified files, and untracked files.

#### Branches and Merging

Git allows you to work on multiple branches, isolating different features or code changes. Here's how to work with branches:

1. Creating a branch: To create a new branch, use the following command:
   ```
   git branch branch-name
   ```

2. Switching branches: To switch to a different branch, use the following command:
   ```
   git checkout branch-name
   ```

3. Merging branches: Once you've made changes in a branch and want to merge them into another branch, follow these steps:
   - Switch to the target branch: `git checkout target-branch`
   - Merge the changes from the source branch: `git merge source-branch`

#### Remote Repositories

Git allows you to collaborate with others by pushing and pulling code from remote repositories, such as GitHub or GitLab.

1. Adding a remote repository: To add a remote repository, use the following command:
   ```
   git remote add origin remote-url
   ```

   Replace `remote-url` with the URL of the remote repository.

2. Pushing changes: To push your local changes to a remote repository, use the following command:
   ```
   git push origin branch-name
   ```

3. Pulling changes: To fetch the latest changes from a remote repository and merge them into your local branch, use the following command:
  

 ```
   git pull origin branch-name
   ```

### Additional Resources

- [Git Documentation](https://git-scm.com/doc): Official Git documentation with in-depth explanations.
- [GitHub Guides](https://guides.github.com/): Guides and tutorials on Git and GitHub collaboration.

Remember, Git is a powerful tool, and this tutorial only covers the basics. Make sure to explore more advanced Git features as you progress in your internship and software development journey.
_Happy Version Controlling_
