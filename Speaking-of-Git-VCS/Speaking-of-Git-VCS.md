# Speaking of Git VCS

## Basic Information

* Lecturer: Mr. Junru Zhong
* Biography:
* Length: 1 hour
* Date & Time: 12:00-13:00, Dec 15, 2017
* Language: Chinese
* Pre-requirement: Install Git software first, bring your laptop. (Installing instruction will be provided later)
* Last modification: Dec 3, 2017

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