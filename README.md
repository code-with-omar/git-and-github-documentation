### What is Git?

- Git is a version control system that tracks changes to files and helps manage code projects.
- It's allows multiple people to work on the same project without overwriting each other's changes.

- Key Features:
  - Tracks history of changes.
  - Helps in branching and merging code.
  - Works offline once installed.

### What is GitHub?

- GitHub is an online platform for hosting and sharing Git repositories.
- It's helps teams collaborate and share projects on the internet.

- Key Features:
  - Stores code in the cloud.
  - Provides collaboration tools (like pull requests and issues).
  - Integrates with Git for seamless workflows.

### Why Do We Need Git and GitHub?

- Git is need for
  - Tracks code changes efficiently.
  - Keeps a backup of the project locally.
  - Allows developers to work independently on features.
- GitHub is need for
    - Stores the project online for easy access.
    - Enables collaboration among team members.
    - Showcases open-source projects to the world.

## 1. Basic Git Concepts
### 1.1 Initialize a Repository - git init
 ```t
    mkdir DIRECTORY_NAME_HERE
    cd DIRECTORY_NAME_HERE
    git init

    Example:
    mkdir notes
    cd notes
    git init
 ```
 ### 1.2 Checking Repository Status - git status
 - Shows the current state of the working directory, including untracked, modified, and staged files.
 ```t
 git status
 ```
### 1.3 Adding Changes - git add fileName/ git add .
- `git add fileName` add a file in staging area / index
- `git add .` add all files of directory to stagging area not subdirectory
- `git add -A` add all files of directory and subdirectory to stagging area
- `git rm --cached fileName` unstage a file from staging area
- `git diff` - checking the differences of a staged file
- `git restore fileName` - restore the file