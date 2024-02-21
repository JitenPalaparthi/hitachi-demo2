1- Create a remote rero
2- Pull the remo to your local system/vm
3- Create a new branch dev
4- Make changes to the branch (create new files)
5- Push files to remote 
6- Create a pull request 
7- Merge them
8- Make changes in the merged files in remote 
9- Make changes to the same file in local
10- git pull origin main : Already some changes are made in remote , there will be conflicts in yoru dev branch.
11- rebase the dev branch with main . git pull origin main --rebase
12- resolve all conflicts
13- Push the branch agann
14- Merge it after creating a pull request 
