# Revisions and the Cloud

* VCS Version Control is a system that lets you revist different saved file versions.
* CVCS Centralized Version Control is a system that entails a single server storing all changes and files, that can be reached by clients.
* DVCS Distributed Version Control systems takes care of the serious vulnerability of the CVS.
* Git
  - Snapshots -> Saves version of your project.
    - Local Operations -> Needed information that can be found in local resources.
      - Tracking Changes -> Everything is tracked through Git. It is the gatekeeper that dose not want corruption.
        - Loss of Data -> With Git irreversible damage to files is greatly reduced.  


## Terminal Commands For Uploading Your Code
* `git add .`                         -> Will get your local changes ready to commit
* `git commit -m "commit message"`    -> saves a snapshot of your code for git
* `git push origin main`              -> push your code changes up to github
* `git status`                        -> if you see files in red, they are not staged. you need to do aall the steps above.
