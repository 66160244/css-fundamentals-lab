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

git checkout branch main
git merge feature/main
git merge feature/css
git checkout main