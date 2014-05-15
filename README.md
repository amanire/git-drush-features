Git
===

### Brief overview

* Committing and log
* Diff  
  ``git diff --cached``
* Ammending commits
* .gitconfig and .gitignore  
  e.g. `git config core.fileMode false`
* Git reset
* Pull vs Fetch and Merge  
  See http://longair.net/blog/2009/04/16/git-fetch-and-merge
* Git aliases  
  e.g. `$ git hist`  
  See http://gitimmersion.com/lab_11.html  
* Git hashes
* Git describe (for tags)

### Merging

* Merging remotes
* Merging local branches
* Resolving merge conflicts

```
git mergetool -t opendiff
git config --global merge.tool opendiff
```

### Rebasing

http://git-scm.com/book/en/Git-Branching-Rebasing

### Github

* Edit/commit UI
* Tags/releases
* Ossue tracker

### Git flow

http://nvie.com/posts/a-successful-git-branching-model  

* Master branch - every commit is tagged and production-ready
* Develop branch - preceeds and is merged to master branch for deployment to production
* Feature branches
* Hotfix branches
* Release branches

**References**  
http://git-scm.com/documentation  

Git - SVN Crash Course
http://git-scm.com/course/svn.html

Drush
====

A command line shell and scripting interface for Drupal

### Commonly-used commands

* cache-clear (cc) - typically, `drush cc all`
* pm-list (pml)
* pm-download (dl)
* pm-enable (en)
* pm-disable (dis)
* pm-update (up)
* user-login (uli)
* variable-set (vset)

### Database commands

* sql-query (sqlq)
* sql-cli (sqlc)
* sql-drop
* sql-sync

### Site aliases

* drush site-alias (sa)

**examples:**  
`drush @hay.dev cc all`  
`drush @hay.local uli`  

* Shell aliases

**References:**  
http://drush.ws  
http://drush.ws/help/examples  
http://drushcommands.com  

Features
======

* Structuring features modules
* Strongarm and variables
* Code structure and direct editing of values
* Reusing features modules for encapsulated code
* Drush commands (fl, fc, fe, fu, fr, fd)

**References:**  
Features & Drush  
https://drupal.org/node/960926
