>>
git checkout -b feature/main 
git add .
git commit -m "create main page"

git checkout -b feature/css
git add .
git commit -m "add basic CSS selectors"

git add .
git commit -m "add box model styles"

git add .
git commit -m "add flexbox laouts"

git checkout main
git merge feature/main
git merge feature/css
git push origin main

git add README 
git commit -m "readme edit"
git push
