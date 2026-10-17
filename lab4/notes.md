Coding Cafe Lab 4.

Question 1
The --global flag applies the Git configuration to all repositories for my WSL user by default. Without it, the settings would only apply to the repository I am currently working in.

Question 2
The .git directory appeared after running git init. It contains Git's internal information, including configuration, objects, and references used to manage the repository's history.

Question 3
Git initially showed about two top-level untracked entries, including .venv/ and week02/. The .venv directory contains installed Python packages and other files that I did not write myself.

Question 4
The .venv directory disappeared from the untracked files list after creating .gitignore. Git now ignores it along with the other patterns specified in that file.

Question 5
Yes, .gitignore should be committed because it defines which files and directories Git should ignore. Tracking it ensures that others using the repository can follow the same ignore rules.

Question 6
README.md moved from Untracked files to Changes to be committed. This means it moved from the working directory into the staging area, ready for the next commit.

Question 7
Git printed the commit identifier, commit message, and a summary of the changes. It reported that 4 files were changed during my first commit.

Question 8
The first seven characters are called an abbreviated commit hash. They help identify and reference a particular commit in the repository's history.

Question 9
The four steps are creating or editing files, checking their status using git status, staging changes using git add, and saving them with git commit. This cycle is repeated whenever we make changes to our project.

Question 10
README.md provides an introduction to the repository, explaining its purpose and contents. GitHub automatically displays the root README on the repository's main page, making it easier for visitors to understand the project.

Question 11
gh auth login authenticated my GitHub account through a browser and configured Git to use GitHub credentials. This allows me to push changes without entering my GitHub password each time.

Question 12
The README.md file appears as formatted text on the front page of my GitHub repository. This happens because GitHub automatically recognizes and renders the README file.

Question 13
Pushing did not change my existing local commits or their history. It uploaded the commits to GitHub and updated the remote-tracking information.

Question 14
A private GitHub repository exists online, but only its owner and authorized collaborators can access it. If the repository does not exist on GitHub at all, there is no online copy for anyone to access.
