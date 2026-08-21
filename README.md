git and GitHub

1st (WORKING DERECTOR)
installation

use the "git bash"
com: cd "file name"    (it is for the changing the directory)
com: cd ..
com: cd ../  (for going to previous file)
com: git clone 'https-link from the GitHub '
com: explorer .  (for opening the file managers)
com: git status (show all states of the working directory and and what is change inside it)
com: git add .
com: git init ( this commend work for the initialize the folder to fit repository in filesystem)

2nd (STAGE)

com: git add --all  / git add -A  (stage every single change across the entire project)
com: git add . (it stage the changes within the current directory you're in)
com: git reset  (it reset the all the change
com: git add *  (it is for the stages all visible changes except for deleted files)
com: git commit -m "I have made some changes to the files" (this commend is use to commit the all the working files)


3rd (LOCAL REPOSITORY)

com: git config --local user.email <YOUR\_MAIL>   (THIS COMMEND IS FOR THE TO CONFIGURE THE LOGIN DETALS )
com: git reset HEAD\~  (THIS COMMEND IS USE FOR THE RESETING THE ALL COMMETED RECORD OR FILES)
com: git reset --hard  (IT CAN BRING THE ALL DELETED FILES TO THE PREVIOUS FOLDERS )
COM: -- force
COM: git rm -f four.txt (you can delete the file force fully)
COM: -- cached
COM: git rm -- cached four.txt (it will delete the file from the commits or virtually and present in the folder)
COM: git rm -r myFolder (IT REMOVES THE ALL FILES INSIDE THE FOLDER )


VIEW COMMITS

COM: git log (IT WILL SHOW ALL THE HISTORY WHAT WE HAVE DONE)
com: git log --oneline (this commend is use for review the previous comits and changes in oneline)


BRANCHING
IN GITHUB AND GIT

CONFLICT
comm: git branch (to see the all branches line "mail" )
com: git branch development (this commend for creating new branch like development )
com: git checkout development (for shifting the branch)
com: git merge main -m "Merging main into development"
com:

MERGE CONFLICT

PUSH
com: git push origin main (it push the all changed files to the GitHub "the main" is nothing but the branch)
com: git checkout staging or development (to push the branches to the GitHub )

TO FETCH
COM: git fetch (this command work for the fetching the changes done)
com: git merge ( the changes will show in the local files )
com: git pull (retrive the changes form the GitHub repo done)

com: git push
com: git fetch
com: git pull

com: git restore --staged .
com: git restore --staged 'filename'



ALL IN ONE

1.
First make nwe folder then make some files inside it
com: git cd filename
com: git cd .. for go back folder or directory
com: git init  (for initialize the folde to git repository from the directory )
