echo "# flamyfox" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M flamyfox/crm-demo-stable
git remote add origin https://github.com/foxgit25/flamyfox.git
git push -u origin flamyfox/crm-demo-stable
