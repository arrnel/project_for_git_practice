Quick setup — if you’ve done this kind of thing before

…or create a new repository on the command line

echo "# project_for_git_practice" >> README.md
git init
git add README.md
git commit -m "Initial commit"
git branch -M master
git remote add origin git@github.com:arrnel/project_for_git_practice.git
git push -u origin master


…or push an existing repository from the command line

git remote add origin git@github.com:arrnel/project_for_git_practice.git
git branch -M master
git push -u origin master

