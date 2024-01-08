# Learnable-git-task

* ### What is Version Control?
    * Version control is a system of tracking and managing changes that are made to files and projects.

* ### What is the difference between git and github?
    * **Git** is a version control system that gives developers the ability to keep track of their projects
    and make changes to that project, it is accessed locally on a users system.
    * **Github** is a web platform or GUI that makes use of Gits version control features to help developers 
    view the changes made in their projects as well as offer additional features like collaboration and pull 
    requests. It is accessible through a browser or an app.
    
* ### 3 Github alternatives
    1. Gitlab
    2. Google Cloud Source Repositories
    3. Radicle

* ### What is the difference between git fetch and git pull?
    * **git fetch**: Git fetch downloads files from a remote repository into the local repository however 
        it does not automatically merge the changes into the working (local) repository. It gives more
        control over when and how changes are integrated.
    * **git pull**: Git pull on the other hand downloads the files/changes from the remote repository and
        automatically merges the changes into the working repository. This can lead to conflicts that need
        to be handled after the pull has been made.

* ### What is git rebase?
    * **git rebase** is a command used to rearrange or merge a sequence of commits in the Git history. 
    It modifies the commit history to appear as though the changes were applied on top of the most recent 
    version of the code, as opposed to combining branches together.
* #### The command for git rebase:
    * git rebase < base >

* ### What is git cherry-pick?
    * **git cherry-pick** is a way of picking a commit from a branch and applying it either to the main
    branch or another branch. It is a technique that enables a developer to pick an arbitiary commit by
    reference and apply it to the working branch.
* #### The command for git cherry-pick:
    * git cherry-pick branchName

    