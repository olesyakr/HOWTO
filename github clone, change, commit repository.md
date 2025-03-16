## HOWTO upload a folder into github
Using command prompt on Windows

1. Clone the repository locally
2. Make the changes to the local version
3. Commit the changes locally
4. Push the changes back up to the GitHub repository

go to desired location (here: brass-plug-counter)
to clone repository
~~~
git clone https://github.com/olesyakr/brass-plug-counter.git
cd brass-plug-counter
~~~

add new folder to the cloned repository
can drag and drop using file explorer or use xcopy C:/<folder location> /s /e

while in repository folder,
add new folder to git (here: training)
```
git add training
```

commit to git
```
git commit -m "added new folder named training"
```

send changes to github
```
git push origin main
```
