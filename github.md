# Git and GitHub
## Git
Git is a version control system. This system records a history of changes made to code as its being developed. These changes are stored in a data base called a repository. GitHub uses Git and hosts these repositories. Once the code is stored in the repository, multiple developers can access the code and make changes to it. Each time a change is made, a comment is added to the code explaining the reason for the change. This is process is called committing. Maintaining access to previous versions of the code allows the developer to revert to them if necessary. Git also allows you to avoid having to save the code into several folders each time you make an update.

## Cloning
Cloning is a process that allow developers to store and edit code on their computers. These edits can be therefore made on a text editor instead of GitHub directly. Several commands on the terminal are used to send these changes to GitHub. These commands are add, commit, and push. Below are examples of these commands.

    git add filename.md

or

    git add *]

These command tells Github that a change has been made and makes them ready to be commited. The first command is used for specific files and the second is used for the whole repository

    git commit -m""

This command tells Github that this is the most recent version of the code. The commit comment is written inside the apostrophes after the -m.

    git push origin main

This command sends or “pushes” the changes to GitHub.

**Note:** Do not make changes to code on directly on GitHub once cloning has used.

Seeing Remotes (Links to an external site.)
When a repository is cloned, the server from which it was cloned from will be called “origin.” When a repository is hosted on the internet, it is called a remote repository or remote for short. These remotes can been seen using a the following commands.

    git remote

This command gives you the names of the remotes.

    git remote -v

This command gives you the name and URLs of the remotes.

[Main Page](README.md)