## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open source Distributed Version Control System (VCS) - it can be used for the storing and tracking of multiple versions of content that can be saved locally and remotely.

2. What is the difference between Git and GitHub?
Git is a VCS that can be installed and run on local machines, while GitHub is a for profit cloud-based git hosting service - it holds stored projects in repositories (folders) and can be accessed using standard git commands in the command-line interface.

3. Why do we create a branch? 
Branches are useful because they are independent lines of code isolate your work from that of any teammates working on the same repository.

4. What is the purpose of a Pull Request?
A pull request is a feature specific to GitHub - it is a summary of your changes in one branch compared to another. It is called a pull request because you will be requesting the main directory to pull changes you've made in your fork and merge them with the original directory

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout -b branch-name


6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The 'git fetch' command downloads changes from a remote repository into your local repository without changing your local files
The 'git merge' command incorporates changes from the named commits into the current branch.
The 'git pull' command downloads changes from a remote repository and merges them into your current branch. It's like running 'git fetch' AND 'git merge'

7. What is a merge conflict?
This is an event that occurs when git is unable to automatically resolve differences in code between two commits. This can happen when people make different changes to the same line of code (eg. when one person edits a file and another deletes the same file). All conflicts must be resolved before a pull request can be successfully merged.

8. How do you resolve a merge conflict?
If Git detects a conflict, it will highlight the conflicted area and ask which code you wish to keep. Once chosen, you can save the file and proceed with the command.
