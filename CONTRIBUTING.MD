###### Pre-requisites:
Install Git: 
*Are you a first time user and just beginning with Open-Source projects? No problem! Here's [how you can install Git on your computer](https://www.digitalocean.com/community/tutorials/how-to-contribute-to-open-source-getting-started-with-git)*

###### After you are done installing Git on your computer:

1. Fork this repository on Github.
2. Clone it onto your computer by opening terminal and running the command
```
git clone https://github.com/{your username}/Algorithms-and-Data-Structures.git
```
3. Use the actual name of the repository to change into that directory (eg. `cd repository`) and create and switch to a new branch by the following command:
`git checkout -b new-branch`
4. After modifying existing files or adding new files to the project, add them locally to your repository using `git add -A` command where A is the file
5. Add a short message about what you contributed for with the git commit command. E.g. `git commit -m "Fixed documentation typos"`
6. Now use the command `git push -u origin new-branch` to push the changes to the current branch of your forked repository
7. Now you can create a Pull Request with the chosen branch as new-branch by going to your repo page on Github.
