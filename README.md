echo "# Test-gallerie-simple" >> README.md

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/steeven-js/Test-gallerie-simple.git
git push -u origin main
