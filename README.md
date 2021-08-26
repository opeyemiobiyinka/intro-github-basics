WHAT IS VERSION CONTROL: Version control system is a very viable system, used by programmers to help them to track and also manage changes made to their files, in the course of executing a project.   It also provide a storage space for files pushed to the remote repository, whenever a change is made to a file or there is a modification of a file, the initial file can be recalled or pulled from the repository.    VCS is a system that fully support team-work and makes team-work very easy and less stressful.  Any of the team members are allowed to access any version of the project depending on the type of version control system used.  Types of VCSs are; 1. Local Version Control systems, which is the first type of VCS used by programmers. 2. Centralized Version Control systems in which the degree to which one developer can  access what another developer is doing is limited.  3. Distributed Version Control system in which the whole history of the project is distributed across all the team members, Examples of a DVCS is Git.

WHAT IS GIT: Git is a type of Distributed Version Control system, it is one of the most widely used VCS today because of its speed and its ability to store data in such a way that every part of the project history can be recovered easily and efficiently.  Git was created by Linus Torvalds in year 2005. It is also a free open source version control system.       unlike the other types of VCSs Git stores data or files in form if snapshots instead if storing the data as a list of changes made on the files over time. This makes it easy to pull data from the remote repository in a minimum amount of time, and also makes it easy to have a maximum recovery of ones files from the reopsitory.

THE PROCESS OF COMMITING A PROJECT TO GITHUB REPOSITORY:
Having Git installed on your pc.
1. Firstly, generate a token which will serve as your password.
2. create your remote repository by visiting github.com, and by following the necessary proceedures.
3. create a folder on your desktop which will house the file which is to be commited to github. 
4. Note that the name of both your local repo folder and that of your remote repo myst be the same.
5. initialize get on your local machine using the "git init" command.
6. Add your file using the command "git add ."
7. Finally, proceed to run your commit by using the command "git commit -m"description"".