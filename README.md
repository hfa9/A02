###Hugo Alvarez A02

What is Git and a Step by step for GIT

Git is distributed version control system that helps you manage and track changes in your project.

Step 1) Download GIT. For windows you can download from the web at https://gitforwindows.org. For Mac you can use homebrew with the command brew "install git".
Step 2) Initialize a Git Repository. Open a terminal or command prompt in your project directory and run "git init". This initializes a new Git repository in your project folder.
Step 3) Adding and Committing Changes. Using the following command you can begin to start adding files to your project. "git add".Once you add a file this stages all changes for the next commit.Now to commit you can do so with a descriptive message about your commit. By using the code "git commit -m "Initial commit".
Step 4)Create and Switch Branches. To create a new branch you run the command "git branch feature_branch" (Feature branch will be the name of the branch that you create). From here to switch to the branch you created you run the command "git checkout feature_branch"
Step 5)Merge Changes. To do so, you will have to switch to the main branch first. Command for this will be "git checkout main". Now to merge the changes from the new branch you created, the command is "git merge feature_branch"
Step 6) Push Changes to Remote Repository. To upload your changes to a remote repository (like GitHub in this case) the command is "git push origin main". 

What is Webstorm and a Step by step for Webstorm

Webstorm is an integrated development environment for JavaScript, HTML, and CSS. It provides tools for web development, including code navigation, intelligent coding assistance, and built-in version control integration.

Step 1) Head to the Webstorm website and download the version based on your operating system. Ex. Windows - https://www.jetbrains.com/webstorm/download/#section=windows. Run the installer and follow the installation instructions.
Step 2) Lauch Webstorm and to start a new project click on "Create New Project". Adjust to your pereferences.
Step 3) Writing the code. Create a new HTML, CSS, or JavaScript File and begin coding. 
Step 4) Version Control Integration. Go to VCS (Version Control System) -> Enable Version Control Integration. Choose Git as the version control system.se the VCS menu to commit changes. Write a commit message describing your changes.
Step 5) Commit and Push. Click the "Commit" button to commit your changes locally. If you want to push your changes to a remote repository (like GitHub in our case), click the "Commit and Push" button.

What is Github and a Step by step for Github

GitHub is a web-based platform that uses Git for version control. It provides a collaborative environment for software development, allowing multiple contributors to work on projects, track changes, and manage versions.

Step 1)Download and Install GitHub Desktop. You can do so from the web or from your store on your computer.
Step 2) Clone a repository. Click on "File", then "Clone Repository" Select the repository you want to clone from the list or enter the repository URL. Choose the local path for the cloned repository. Click "Clone."
Step 3) Make Changes, Commit, and Push. Open your project in VS code. Make changes to it as you wish. In github click "Commit to main." After committing changes, click "Push origin" to upload your changes to GitHub.

### Glossary

- **Branch:** A parallel version of a repository that allows you to work on different features or fixes.
- **Clone:** Create a copy of a repository on your local machine.
- **Commit:** Record changes to the repository with a descriptive message.
- **Fetch:** Download changes from a remote repository.
- **GIT:** A distributed version control system.
- **Github:** A web-based platform for version control using Git.
- **Merge:** Combine changes from different branches.
- **Merge Conflict:** A situation that occurs when Git cannot automatically resolve differences between merged branches.
- **Push:** Upload local changes to a remote repository.
- **Pull:** Download changes from a remote repository to your local machine.
- **Remote:** A repository hosted on a server.
- **Repository:** A project's version-controlled directory.

