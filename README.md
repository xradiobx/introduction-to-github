# introduction-to-github

echo "# introduction-to-github" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/xradiobx/introduction-to-github.git
git push -u origin main

name: Post welcome comment
on:
  pull_request:
    types: [opened]
    
