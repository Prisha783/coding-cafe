#question 1:
--global means the git configuration applies to all repositories for the current user. If we leave it out,
the setting applies only to the current repository if configured there. 

#question 2:
ls-a shows hidden files and folders that ls normally does not display. One important hidden folder 
is.git which contains Git's repository information and history.

#question 3:
Git offers to track the files and folders listed as untracked. Some may be files I created while 
others such as Python cache files or virtual environment files may be automatically generated 
and not written by me.

#question 4:
After creating .gitignore, files and folders matching its rules disappeared from the untracked files list because 
Git was instructed to ignore them.

#question5:
.gitignore should be committed, not ignored. It tells Git which files to ignore and tracking it lets other people working on
the same project use the same rules.


#question 6:
README.md moved from Untracked files to changes to be committed. This happened because I ran git add README.md which 
staged the file for the next commit. 
#question 7:
Git printed a summary of the commit including the number of files changed and the insertions. In my commit, Git reported
4 files changed and 373 insertions. 

#question 8:
The first seven characters of the commit ID are the short commit hash. They identify that particular commit and can be used to 
refer to in Git commands.
#question 9:
first we checked the git status then we staged the changes and then saved them in gut history. Finally we viewed the commit 
history.
#question10:
README.md gives readers an introduction to the project and explains its contents. It is usually placed in the main folder so 
that people can find it easily unlike notes.md which contains specific notes. 
