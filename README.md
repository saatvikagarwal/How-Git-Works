# How Git Works!
#### Github tutorial from pluralsight (How Git Works)

### Module 1:-

  Git calculates the hashes with SHA-1 Algorithm. Every peice of content has its own SHA-1

  git command (it's a low level plumbing command) to calculate SHA-1 
   ###### echo "Apple pie" | git hash-object --stdin
   ##### first commit:-
   ###### git init 
This command initializes empty git repository.

###### git status
This command displays the state of the working directory and the staging area.

###### git add filename
This command adds the file which we have specified to our repository.

###### git add .
To add all the files present in directory to repository.

###### git commit -m "message"
This command is used for saving changes.

###### git log
This command is used to look at the list of existing commits.

###### git tag -a mytag -m "message"
Annotated tags ( A tag that has its own commit hash and is, as such, stored as a separate object in git.)

### Module 2 (Branches Demystified) :-

###### git branch
This command will get a simple listing of our current branches.

###### git branch branchname
To create a new branch (it will have same contents as of master branch)

###### git checkout branchname
move HEAD and update the working area (Switch to a branch)

###### git merge branchname
Merge a branch into the active branch

