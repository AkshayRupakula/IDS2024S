**1.** File Created!  
**2.** `.md` stands for markdown and the period before it indicates the file type. We prefer to use .md files on github since they can be previewed on page where it is stored.  
**3.** No, Git does not track empty folders by default. Git focuses on tracking changes to files rather than the directory structure itself. Empty folders are not considered as changes to track.  
**4.** Yes every git project has a .git folder  
**5.** .git folder is essential for Git to function and manage the version control of your project effectively. It encapsulates all the necessary information and configurations needed for version control operations.  
**6.** cd = Change directory  
**7.** ls -a = Formatted List all files and hidden files  
**8.** pwd = Print working directory  
**9.** The three different areas in a Git project are: 
* Working Directory: This directory contains the file that is being modified by the user but Git has no track of the file changes. If the file is lost or removed, Git cannot recover it.  
* Staging Area: When a file is modified it can be added to the Git staging area and committed at a later time. The staging area contains files in the repository and stores info about the next commit to the repository.  
* Local Directory: After the files in the staging are committed to the repository, they can be seen on the github and can be accessed at later times.
**10.** Version control is a software-based system that records changes to a file or set of files over time so that you can recall specific versions later making teamwork, collaboration, and maintenance easy for teams and larger organizations.  
**11.** The 6 benefits of using distributed VCS as opposed to not using any VCS at all for project indexing and maintenance are:  
* Robustness and Redundancy  
* Flexibility in Collaboration  
* Improved Performance  
* Enhanced Security  
* Offline Capability  
* Better Branching and Merging  
**12.** Three major classes of Version control systems (VCS) are:  
* Local VCS  
* Centralized VCS  
* Distributed VCS  
**13.** git vs GitHub  
* Git: Distributed version control system designed for tracking changes in source code. It operates locally on a user's machine.  
* GitHub: Web-based platform that provides hosting for Git repositories and adds collaboration features such as issue tracking, project management tools, and code review functionalities.  
**14.** git status = Check the status of the project  
**15.** git push --all = Push all the file changes in the local repository to the remote repository  
**16.** git pull = Fetches changes from the remote repository to the current branch in the local repository and immediately attempts to merge them into the branch from which it was called. It's a way to ensure that your local repository is updated with any changes made by others in the team.  
**17.** Markdown is a markup language used for formatting plain text documents. It's commonly used for writing content for the web, such as README files, documentation, forum posts, and more. Markdown allows users to easily add formatting elements like headers, lists, links, and emphasis using simple syntax, making it accessible and intuitive for writers.  
**18.** Use a double asterisk or underscore before and after the word/sentence you want bold.  
**19.** Use a single asterisk or underscore before and after the word/sentence you want in italics.  
**20.** git init (directory name)  

**21.** The difference is:  
* . refers to the current directory.  
* .. refers to the parent directory.  

**22.** 
* ls -a  
* mkdir testdir  
* cd testdir  
* git init  

**Extra Credit:** What is the difference between a relative and an absolute file path? Which one is more appropriate to use in your GitHub projects? Why?  
* Relative and absolute paths are two methods used to specify the location of a file or directory within a file system. An absolute path provides the complete address starting from the root of the file system, ensuring that its location is always unambiguous, regardless of the current working directory. In contrast, a relative path specifies a file or directory's location to the current working directory, making it a more flexible and sometimes shorter way to navigate the file system.

**Extra Credit:** Write down the Git command that lists all Git commands for you:
* git init
* git pull
* git push
* git commit -m""
* git status
* git log
* git help -a

