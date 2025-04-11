# DevOps Git Project

This repository is created as part of **Task 4** of my DevOps Internship. The task focuses on learning and demonstrating proper Git practices including version control, branching, pull requests, tagging, and using GitHub workflows.

## 📌 Task Objective

Manage a DevOps project using Git best practices such as:
- Creating branches (main, dev, feature)
- Writing meaningful commits
- Opening and merging pull requests
- Using `.gitignore` and Git tags
- Documenting project structure and commands

---

## 🧰 Tools Used

- Git
- GitHub
- Bash / Terminal

---

## 🔧 Project Structure

```bash
devops-git-task/
├── app.js               # Hello World JavaScript file
├── README.md            # This documentation
└── .gitignore           # Ignored files and folders

```
# Initialize Git and first commit
git init
git add .
git commit -m "Initial commit with README and .gitignore"
![image](https://github.com/user-attachments/assets/af9e396b-666e-4ba5-8cf8-44313485b5e6)


# Create branches
git branch -M main
git checkout -b dev
git checkout -b feature/hello-world
![image](https://github.com/user-attachments/assets/a623e35b-2dfa-4d1d-b9b2-c6965941fe1c)


# Add a sample file and commit
echo 'console.log("Hello, DevOps!");' > app.js
git add app.js
git commit -m "Add hello world script"
![image](https://github.com/user-attachments/assets/41e4a1ec-e211-4255-b1e2-6394046e065d)


# Link to GitHub and push
git remote add origin https://github.com/vikashchaurasiya07/devops-git-task.git
git push -u origin feature/hello-world
![image](https://github.com/user-attachments/assets/21f698d8-4420-4ed4-a56e-4b9018aa63ae)


# Create and merge PRs on GitHub UI

# Tagging a release
git checkout main
git tag -a v1.0 -m "Version 1.0 release"
git push origin v1.0
![image](https://github.com/user-attachments/assets/0e4ddf55-6db9-44c1-ae80-d401fdec6eb6)



node_modules/
.env
*.log


