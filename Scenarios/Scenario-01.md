## Scenario 01

Create a local repository on empty folder

1. Create an empty folder, named “scen01”
2. Create a new repository on your GitHub. Named “scen01”
3. Keep configuration as default
4. Copy its URL
5. Run the commands as ordered

```
md scen01
cd scen01
git init
git remote add origin <url>
git remote -v
echo “hello world!” >> hello.txt
git status
git add .
git commit –m “init commit”
git show
git push --set-upstream origin master 
```
