# devsecops-tasks-girishn
devsecops-tasks-girishn

# DevSecOps Git Practice - GIRISH N
## Date: 04-08-2025

### 🔧 Git Configuration
git config --global user.name Girish N
git config --global user.email girishn9@gmail.com
git config --list

### 📁 Repository Setup
git clone git@github.com:girishn9/devsecops-tasks-girishn.git
cd devsecops-tasks-girishn
mkdir 04-08-2025
cd 04-08-2025
touch task1.txt task2.txt

### 📦 Staging and Committing
git status
git add .
git commit -m "Initial commit with two task files"

### 🔁 Making Changes
echo "This is Task 1 content" >> task1.txt
git status
git add task1.txt
git commit -m "Updated task1.txt with content"

### 🧾 Logs and Show
git log
git show 7fceb80

### 🚀 Push to GitHub
git push origin main

### 🔁 Pull Remote Changes
git pull
