# GUIDES
Create a new repository on the command line
echo "# guides" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:asaguado/guides.git
git push -u origin master

Push an existing repository from the command line
git remote add origin git@github.com:asaguado/guides.git
git branch -M master
git push -u origin master
