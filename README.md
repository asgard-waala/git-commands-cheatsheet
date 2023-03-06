# git-commands-cheatsheet
> A quick reference to the Git commands.
---
- Configure user information for all local repositories: 
  1. `git config --global user.name "[name]"` : *Sets the name you want attached to your commit transactions*
  2. `git config --global user.email "[email address]"` : *Sets the email you want attached to your commit transactions*
  3. `git config --global color.ui auto` : *Enables helpful colorization of command line output*
  ---
- Create an empty Git repository or reinitialize an existing one
  1. `git init [repository name]`
  ---
- Clone a repository into a new directory
  1. `git clone [URL]`
---
- Add file contents to the index
  1. `git add [filename]`
  ---
- Show the working tree status
  1. `git status`
  ---
- Show changes between commits, commit and working tree, etc
  1. `git diff` : *Shows the file differences which are not yet staged.*
  2. `git diff –staged` : *Differences between the files in the staging area and the latest version present.*
  3. `git diff [first branch] [second branch]` : *Differences between the two branches mentioned.*
  ---
- Record changes to the repository
  1. `git commit -m "[Type in the commit message]"` : *Use the given **message** as the commit message. If multiple -m options are given, their values are concatenated as separate paragraphs.*
  2. `git commit -a` : *Tell the command to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected.*