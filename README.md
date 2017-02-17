# git-note
Helps to create and list notes for the git branches

Solution is taken from [this question](https://stackoverflow.com/questions/4750845/how-do-you-annotate-a-branch)

Script is copied from [this link](https://bitbucket.org/rkj/dotfiles/src/310059118a22bc3fba5227c13e5028e5d4c71499/bin/git-note?at=default)

## Requirenment
Ruby >= 1.9

## Usage

Copy the script somewhere to the /bin directory (that is in your PATH) 
```
$ git note "Some note" # set note for current branch
$ git note -b branch # see note for branch
$ git note -l # list all the branches with theirs' notes
```
