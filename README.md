#HELLO WORLD
This is the file that I have created to learn the concepts of GIT
And currently I am trying to push more than one files on my repository.
The commands are :
git --version (To check the version of my git and whether git is installed in my pc)
git status (To know the status of the files whether they are tracked or untracked) 
            For tracked files, git keeps the track of all the changes that have been made in the file
            For untracked files, git does not keep the track of any changes that have been made. For these kind of files, git just knows that a new file has been created
git add file_name : This command is used to enable tracking in the file such that git can keep 
                    the   track of the changes in the file 
git add --all : This command is used to enable tracking on all the files in the current folder in 
                the local storage.(git add -A)
git commit -m "COMMIT MESSAGE" : Only after running this command, git starts keeping the track of 
                all the changes that have been made in all the files where we have enabled tracking such that we can return later in the previous version if we want to find te bug in the code. The -m command is used for adding a message to the commit such that We can clearly know what all changes had been made in the commited version   
git status --short : This command is used for displaying a short descrption about whether the 
                    files have been changed or not 
git commit -a -m "Message" : This command is used to commit to the repository without staging in 
                    the case of minor changes.
git log : This command is used to logging the history of all the changes that have been made in 
            the repository.
            In git, the branch is the new and separate version of the main repository.
git branch branchname : This command is used to create a new branch of our repository. Working on 
                one branch wont effect the other branch. Lastly, we can merge the new branch with the main branch after fixing errors of after working on different interfaces.
Changed the readme file again
