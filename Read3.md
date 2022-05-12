# **Git Introduction**

*Git* is defined as a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project - called committ. Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. Git mostly relies on local operations.Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git traces its roots to the open source software project Linux kernel. *Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

Prerequisites to understanding Git is based highly on your understanding of the aspects of *Version Control*. So what is Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System VCS, mistakes with files can easily be rectified.

## Types of Version Control

1. *Local Version Control* which entails one database on your hard disk that stores changes to files.
2. *Centralized Version Control* this system entails a single server storing all changes and file versions, which can be accessed by various clients.
3. *Distributed Version Control* addresses the major vulnerability of the CVS: the server as a single point of failure.

*Download Git*
In order to use Git, your computer must have it available. Git can be installed in three ways:

1. Install as a package
2. Install via another installer
3. Download and compile the source code.

*Git Installation Complete* to ensure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine. To change settings, you can repeat these steps.

Step 1. **Configuration of Variables**
An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

Step 2. **Identity Setting**
After installing Git, users should immediately set the user name and email address, which will be used for every Git commit. Type the following into Terminal or Command Line: git config --global user.name "Jane Smith"

### Local Repository Structure The local Git repository has three components

1. *Working Directory*: The actual files reside here.
2. *Index*: The area used for staging
3. *Head*: Points to the most recent commit

*The git remote comamand provides you with two results:*

1. By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.
2. By using git remote -v, you can view all the remote URLs next to their corresponding short names.
