1) INSTALLING GIT:

    Step 1: Open the Terminal and  type  
     
     sudo apt update
     
     sudo apt install git

2) CONFIGURING GIT:

    Step 1: Go back to the terminal and type this to configure git

    git config –global user.name “your_username”

    Step 2: Now type this to link your email too.

    git config –global user.email “your_emailid”
   
3) CREATING GITHUB ACCOUNT:

4) CREATING GITHUB REPOSITORY

5) CLONING REPOSITORY

    git clone https://github.com/basilky/testrepo.git
   
6) ADDING A NEW FILE (calc program addition func)
   
    git add filename
    git status
    
7) COMMITS
    
    git commit -m "message"
    git log
    
8) REVERTING CHANGES
    
    git revert lastcommitid
    git reset --hard commitid
    
9) GIT PUSH

    git push
    
10)DELETING AND AGAIN CLONING
