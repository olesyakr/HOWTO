1) open Git, navigate to desired folder on local machine (ex C://Git)
2) git clone _insert URL from repository here_ ex:
   **git clone https://github.com/ORGANIZATION/MY_REPOSITORY_FOLDER.git**
4) navigate to cloned branch
 **cd MY_REPOSITORY_FOLDER**
6) create and switch to development branch:
   **git checkout -b development**
8) **code .**  command (with dot) will open VS code
9) switch to VS code, make changes in VS code IDE, save
10) go back to Git Bash, check files: **git status**
11) stage all changes in folder: **git add .**
12) **git commit -m "my first commit to the development branch"**
13) **git push --set-upstream origin development**
14) go to Github to check changes
