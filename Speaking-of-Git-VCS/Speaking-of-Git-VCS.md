# Speaking of Git VCS

## Basic Information

* Lecturer: Mr. Junru Zhong
* Biography:
* Length: 1 hour
* Date & Time: 12:00-13:00, Dec 15, 2017
* Language: Chinese
* Pre-requirement: Install Git software first, bring your laptop. Installation guide click <a href="https://github.com/UICHCC/HCC-Lectures/blob/master/Speaking-of-Git-VCS/Installation-Guide/Installation-Guide.md">here</a>.
* Last modification: Dec 6, 2017

## Outline

* History, purpose of version control system
* History of Git
* Concept clarify: Git & GitHub
  * Git: A version control system
  * GitHub: A company / website provides Git repository hosting
* **Git Workflow**
  * Distributed repository model *vs. centralized model*
  * **Main steps**
    * Initialize a Git repository: `git init`
      * *Remember to add a `.gitignore`  file.*
    * Modify some file
    * Stage changes `git add .`
      * See difference `git diff`
    * Commit changes `git commit`
      * Write commit message
      * *Principles of commits*
    * Push changes to remote `git push`
      * Set up remote repository
      * Tell me about you
  * Collaborating with people
    * Using GitHub
    * Forks, issues, pull requests
    * Handling conflicts
* More than main steps
  * Tracking status `git status`
  * Find out what's new `git pull`
  * Roll-back changes
  * Make your repository clear `git rebase`

## Detail Contents

### Purposes of Version Control System

**Hook: Problems of sharing code**

* Using IDE: Sending files which are not **source file** will cause problems

  *Workspace configuration of Intellij platform saved in the project*

  **Configuration file** vary in different installation (computer)

  **Only source files are needed to be transfer.**

* Sending **source code** *files*

  *Modifications will be covered* -> Even worse when multiple modifications happen.

  *Which part of the code was modified? Who made this modification?*

  **Tracking modifications, when, where, and who.**

* Sending files through IM software

  *Files expired*

  *Flooded by chat record*

  **A way specified for developers**

**Main Purposes of VCS**

* Transferring source code (or any other plain text)
* Tracking modifications
* Sharing your achievements

### Git: a popular version control system

**What is Git**

* A distributed source code management software
* Developed by Linus Torvalds for Linux kernel development in 2005.
* Network connection is not required unless you want to *push* your code to a remote *repository*

**Phases in Git**

* Managing your own code
  * Repository (仓库)
  * Working files (工作文件)
  * Stage (暂存区)
  * Commit (提交)
  * Branch (分支)
  * Revert (恢复)
  * Rebase (变基)
* Working with others
  * Clone (克隆)
  * Fork (岔出)
  * Pull (拉取)
  * Push (推送)
  * Issue (议题)
  * Pull request (合并请求)

### Git workflow

To be continued...