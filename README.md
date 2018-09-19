2018-09-19 By Patrick Steranka

This repo exists to support testing .gitignore patterns for ignore some temp files
that have the hash (#) character in them.

The stackoverflow question I asked is at: 
https://stackoverflow.com/questions/52391883/what-is-the-pattern-for-gitignore-to-ignore-temp-filenames-with-in-them

I realized after creating this repo that I didn't want to commit the temp files that I
didn't want to commite so I created short scripts to create the temp files and remove them.

To experiment do the following.  I state what to do along with giving you the command to run.

(1) Clone this repo.  You've done this if you are seeing this.

    git clone git@github.com:steranka/git-ignore-test.git
    cd git-ignore-test

(2) Create temp files

    bin/create-temp-files

(3) See that the temp files appear in git status.

    git status

(4) Copy the use-this-gitignore into place and see that the files are filtered out by git status.

    cp use-this-gitignore .gitignore
    git status

Experiment if you wish.

