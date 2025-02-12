# UEF

This is a working repository for a course about versioning with Git, data repositories in general, and other related things.

## How to start with Git
1 Clone this repository to your own computer. The clone will be your local working repository.
  - open Terminal application
  - find or create the folder into which you want to clone the repository (e.g. Unix: `cd FOLDERNAME` or `mkdir FOLDERNAME`)
  - execute `git init`
  - execute `git clone https://github.com/meehka/UEF`

2 Edit files in the repository locally on your computer

3 Commit your additions, corrections or other editions to the remote master repository
  - go to Terminal application or open it again
  - execute `git commit -m "YOUR LOG MESSAGE" FILENAME`
  - execute `git push`
The command `git commit` stages all changes that you have made, the command `git push` finally sends these changes to the remote master repository, so that it will be updated and visable for your collaborators.

4 Every time **before** you start working on files in this repository on your computer:
- open Terminal application
- go to the folder with your working repository
- execute `git pull` (in order to get the newest version)
Now, the files on your local working repository will be compared with the files on the remote master repository (where your collaborators may have been working in the meanwhile).

5 Make commits often during your work, but especially when you finish (in order not to end up in version conflicts)

6 Add a new file or folder
- create the file/folder in your local working repository (e.g. Unix: `touch FILENAME` or `mkdir FOLDERNAME`or `mv FOLDERNAME(OLD)/FILENAME(OLD) FOLDERNAME(NEW)/FILENAME(NEW)`)
- execute `git add FILENAME(NEW)` (if you are in this folder)
- execute `git commit -m "YOUR LOG MESSAGE" FILENAME(NEW)`
- execute `git push`

7 In order to see the list of changed files:
- go to Terminal application or open it again 
- execute `git status`
Now, you will get an information about all files, that were changed.

## Useful links
- [Git](https://en.wikipedia.org/wiki/Git)
- [Tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world)
