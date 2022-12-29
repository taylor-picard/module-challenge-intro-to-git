## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
    Git is a version control system that tracks changes in files.
2. What is the difference between Git and GitHub? 
    Git is a software and command-line tool installed locally on the system. GitHub is a web hosted cloud service to manage Git repositories.
3. Why do we create a branch? 
    To edit the main code on our own copy without effecting the actual main code.
4. What is the purpose of a Pull Request? 
    To let other developers know about the changes you've pushed to your branch in a repository so they can review those changes and start the process of integrating new code or fixes.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
    Use either 'git checkout main' or 'git switch main'
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    'git fetch' is used to fetch a remote branch
    'git merge' is used to integrate different branches of code into a single branch
    'git pull' is used to retrieve updated content from a remote repository and download it to the local repository.
7. What is a merge conflict?
    When different commits have conflicting changes to the same line of code.
8. How do you resolve a merge conflict?
    Identify the files affected. Use a text editor to open the file, then search the file for the conflict marker. Decide which of the changes you want to keep or create a new change. Delete the conflict markers, then add, commit, and push the file again with the final change.
