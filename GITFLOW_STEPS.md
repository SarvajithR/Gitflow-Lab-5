# Gitflow Lab 5 - Command Record

```bash
git status
git checkout -b develop
git push -u origin develop

git checkout -b feature/login
git add app.py
git commit -m "Add login feature"
git push -u origin feature/login

git checkout develop
git merge feature/login
git push origin develop

git checkout -b feature/conflict
git add README.md
git commit -m "Update README for conflict feature"
git push -u origin feature/conflict

git checkout develop
git add README.md
git commit -m "Update README on develop"

git merge feature/conflict

# Resolve README.md in VS Code, then:
git add README.md
git commit -m "Resolve merge conflict"
git push origin develop
```
