## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    Git is a free open source distributed version control system.
2. What is the difference between Git and GitHub?
    Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.
3. Why do we create a branch? 
    To modify code and created changes without effecting the main branch.
4. What is the purpose of a Pull Request?
    Pull requests let you tell others about changes you've pushed to a branch in a repo.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
    git checkout main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    'git-fetch' - Download objects and refs from another repository. 'git-merge' - incorporate changes from another repository and can be used by hand to merge changes from one branch into another. 'git pull' - Fetch from and integrate with another repository or a local branch. Incorporates changes from a remote repository into the current branch.
7. What is a merge conflict?
     A merge conflict is an event that occurs when Git is unable to automatically resolve differences in code between two commits.
8. How do you resolve a merge conflict?
    After seeing a conflict, you can do two things:
    1. Decide not to merge. The only clean-ups you need are to reset the index file to the HEAD commit to reverse 2. and to clean up working tree changes made by 2. and 3. git merge --abort can be used for this.

    2. Git will mark the conflicts in the working tree. Edit the files into shape and git add them to the index. Use git commit or git merge --continue to seal the deal. The latter command checks whether there is a (interrupted) merge in progress before calling git commit.

Hello!!!!!!