## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
	Git is an open source software for coordinating work among programers, helping with Version Control.
2. What is the difference between Git and GitHub?
	The difference between Git and GitHub is that Git is a software for version control and software development and GitHub is a hosting service for Git where software can be uploaded for collaberation and approval.
3. Why do we create a branch?
	We create a branch so that when we push the software back to Git after editing the original data isnt messed with and our changes can be viewed by an admin for approval as well as be traced back to us if something else needs to be done. 
4. What is the purpose of a Pull Request?
	The purpose of a Pull Request is to let the admin know that we are ready for our branched code to be integrated into the original version.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
	To switch back to the main branch you would use "git switch" to create a new branch you can use "git checkout"
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
	"git fetch" will gather ant new commits from the branch that differ from the current branch. It will not merge the two branches and leaves them seperate. "git merge" merges the pulled in commits from "git fetch" with your current branch. "git pull" more or less combines these two steps into one but will not give you a chance to review any new commits before writing them to your branch.
7. What is a merge conflict?
	A merge conflict occurs when two branchs of code are being merged that have conflicting code. Git will merge most new files in without a problem but a merge conflict will occur when one developer deleted a section of code entirely and another developer edits the same file.
8. How do you resolve a merge conflict?
	To resolve a merge conflict you must manually edit the conflicted file to choose which changes you want to keep. you can do this through the conflict editor on GitHub or you can creat a local clone of the repositiory, edit it, and push the change to your branch.
