# README

### To set up a local repository, do the following steps

- Navigate to the folder where the repository is intended to reside

- Initialize an empty repository using:
    >     git init

- After initialization confirm git status using:
    >     git status

- The add files in the repository using:
    >     git add .

- Commit changes to the local repository using
    >     git commit

- In Vim type a meaningful commit message and then commit

### To set up a remote repository, do the following steps
- Create a remote repository on GitHub

### To link the local and remote repositories together, do the following steps

* Link the local repo with the remote one using:
    >     git remote add origin “remote url(preferably ssh)”

* To confirm the local to remote connection use:
    >     git remote -v

* To fetch files from the remote repo to your local repo use
    >     git pull origin main

* Then perform a rebase or merge so as to reconcile the conflicting branches (if any conflict arises)
    - To reconcile using rebase use:
        >     git config pull.rebase true
    - To reconcile using merge use:
        >     git config pull.rebase false
    
* Then perform the pull again so as to finalize the reconciliation

* Then push your staged changes from your local repo to the remote repo using:
    >     git push origin main