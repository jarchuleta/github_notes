###Bitbucket

Set up your local directory
Set up Git on your machine if you haven't already.
```
mkdir /path/to/your/project
cd /path/to/your/project
git init
git remote add origin https://james@bitbucket.org/james/test2.git
```
Create your first file, commit, and push
```
echo "James Archuleta" >> contributors.txt
git add contributors.txt
git commit -m 'Initial commit with contributors'
git push -u origin master
```

Already have a Git repository on your computer? Let's push it up to Bitbucket.
```
cd /path/to/my/repo
git remote add origin https://james@bitbucket.org/james/test2.git
git push -u origin --all # pushes up the repo and its refs for the first time
git push -u origin --tags # pushes up any tags
```
