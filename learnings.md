## 5 Things I have learned about Git and GitHub

- git is the version control software whereas Github hosts remote repositories
- workflow for working in local machine: git add <filename(s)> ==> git commit -m "<succint description of the commit>" ==> git push
- before starting to work on a collaborative project, a developer should always start with git pull so that all the changes made by other team members are loaded to 
their system
- git checkout -b <branch-name> does two things at once: git branch <branch-name> + git checkout <branch-name>
- most things that we can do in the IDE of our local machine, can also be done on github website. there are, however, some subtle differences such as when changes 
are made to the repo on github website, we do not have to do git push since changes already being done to the remote repo.


## 2 more things I have learned about Git and Github

- we can keep git from tracking files or folders by including a .gitignore file in our directory where the name of the files and folders not to be tracked will be 
listed
- two types of merge: fast-forward and three-way 