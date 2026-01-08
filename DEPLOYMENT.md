# Deployment – The Bard's Bytecode

## 1. Create the repo

On GitHub:

1. Create a new **public** repository, e.g. `the-bards-bytecode`.
2. Don’t add any files via the UI (or be ready to pull & merge first).

Locally, from inside your project folder:

```bash
cd path/to/the-bards-bytecode

git init
git add index.html bard.spl README.md DEPLOYMENT.md
git commit -m "Initial commit: The Bard's Bytecode"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/the-bards-bytecode.git
git push -u origin main
