# **Git**
When working on a project, especially if you are a member of a team, it is common to have many edits on the files of the project while it is still in development, which leads to different versions of the same file, which in turn leads to sometimes either losing track of changes or even worse, to lose all of your data.

--------

**What is Git?**

In summary, Git is a version control system that makes it easier to trach changes and all the different versions of a file you alone or you and your team are working on. In contrary to centralized version control systems, Git is a distributed version control system (DVCS), which means that every user creates a change on the file at hand, Git creates a copy of that file locally without the need to save them to a shared server, the thing that eleminates the possibility of losing data, in addition to the ability to work in your files even when you are offline or connected to a VPN.

-------

*To install Git you can refer to this website (Links to an external site.) for help.

*As for any other software to help you go through your project, you will have to install Git on your machine, then to register and provide some information about you, in additon to some knowledge about the terminal.

**With Git, you clone (copy) all versions of the file you are working on, and Git automatically retrives any new versions of the file when they undergo modification or editing.*

Git's workflow
Local Repository Structure


-------------

***The local Git repository has three components:***

1. Working Directory: The actual files reside here.
2. Index: The area used for staging (staging means flagging a file’s changed version to be committed in the next snapshot)
3. Head: Points to the most recent commit