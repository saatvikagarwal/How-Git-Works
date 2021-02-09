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

### Module 3 (Rebase) :-

###### git rebase master
Merges preserve history whereas rebases refractor history.

###### git tag
A tag is like a branch that doesn't move.

### Module 4 (Distributed Version Control):-

###### git clone repositoryURL
This command only clones the master branch.

###### git branch --all
to view all references

###### git show-ref master
Displays references available in a local repository along with the associated commit IDs.

###### git push
The git push command is used to upload local repository content to a remote repository.

###### git pull
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

###### git fetch
The git fetch command downloads commits, files, and refs from a remote repository into your local repo.

###### git fork
A fork is kind of a clone but it's a remote clone.


