1. [Here is the README file I created](../../README.MD)  

2. Local, Centralized, Distributed  

3. The "best" VCS depends on specific needs, workflow, team size, and project requirements. However, Distributed Version Control Systems (DVCS) are often considered superior for several reasons:  
* Robustness and Redundancy: With DVCS, every checkout is a full backup of the repository. This redundancy protects against data loss.  
* Flexibility in Collaboration: DVCS supports various workflows – centralized, feature-branch, gitflow, forking, etc., making it adaptable to many project and team sizes.  
* Improved Performance: Operations like commit, branch, merge, and history are faster in DVCS because they are performed locally.  
* Enhanced Security: The distributed nature of DVCS allows for using cryptographic methods to authenticate history, ensuring the integrity of the codebase.  
* Offline Capability: Developers can work completely offline (commit, branch, merge), syncing up with the main repository once they have internet access again.  
* Better Branching and Merging: DVCS systems like Git are designed with branching and merging as first-class operations, making these tasks easier and more intuitive than in CVCS.  

4. * a. **git pull:** This command fetches changes from the remote repository to the current branch in the local repository and immediately attempts to merge them into the branch                          from which it was called. It's a way to ensure that your local repository is updated with any changes made by others in the team.  
   * b. **git status:** This command displays the state of the working directory and the staging area. It shows which changes have been staged, which haven't, and which files aren't                         being tracked by Git. It's useful for getting a quick overview of the current state of your project.  
   * c. **git add --all:** This command stages all changes in your working directory for the next commit. This includes new files, deleted files, and modified files. It's a way to                              prepare all your changes to be committed at once.  
   * d. **git commit -m"latest build":** This command commits the staged changes to the local repository with a commit message "latest build". Committing changes records a snapshot                                           of the project in Git's history, allowing you to track progress and revert to previous states if necessary.  
   * e. **git push --all:** This command pushes all of your local branches to the remote repository. It's useful when you want to update the remote repository with all the branches 
                            you've worked on locally, not just the current branch. This ensures that all your local branches are backed up remotely.  

5. Completed in class

6. 
* a. HTTPS stands for HyperText Transfer Protocol Secure. It is the secure version of HTTP, the protocol over which data is sent between your browser and the website that you are connected to. The 'S' at the end of HTTPS stands for 'Secure'. It means all communications between your browser and the website are encrypted. HTTPS is often used to protect highly confidential online transactions like online banking and online shopping order forms.  
* b. Relative and absolute paths are two methods used to specify the location of a file or directory within a file system. An absolute path provides the complete address starting from the root of the file system, ensuring that its location is always unambiguous, regardless of the current working directory. In contrast, a relative path specifies a file or directory's location to the current working directory, making it a more flexible and sometimes shorter way to navigate the file system.  
