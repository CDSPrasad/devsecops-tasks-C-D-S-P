# DevSecOps Git Practice - prasad
## Date: 2025-08-08

### 🔧 Git Configuration
git config --global user.name "prasad"
git config --global user.email "chinthaprasad405@gmail.com"
git config --list

### 📁 Repository Setup
git clone https://github.com/CDSPrasad/devsecops-tasks-C-D-S-P.git
cd devsecops-tasks-C-D-S-P
mkdir 2025-08-08
cd 2025-08-08
touch t1.txt t2.txt

### 📦 Staging and Committing
git status
git add .
git commit -m "Initial commit with two task t1 t2 files"

### 🔁 Making Changes
echo "This is Ta1 content" >> t1.txt
git status
git add t1.txt
git commit -m "Updated t1.txt with content"

### 🧾 Logs and Show
git log
git show <commit-id>

### 🚀 Push to GitHub
git push origin main

### 🔁 Pull Remote Changes
git pull

## 🔄 Task 4: Update and Push

1. Keep making small changes to task files, commit, and push.

2. Ensure all changes and git commands are recorded in README.md
