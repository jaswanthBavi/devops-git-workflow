# DevOps Git Workflow 🚀
This project demonstrates a Git-based version control workflow following DevOps best practices. It includes branch strategies, pull requests, tagging, and documentation using markdown.
## 📌 Project Description
This repository is part of the **ElevateLabs DevOps Internship - Task 4**, where the goal is to manage a project using Git best practices. It includes:
- Branching strategy (`main`, `dev`, `feature/*`)
- Pull requests and merge strategy
- Version tagging
- Usage of `.gitignore` and `README.md`
---
## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/jaswanthBavi/devops-git-workflow.git
   cd devops-git-workflow
View available branches:
bash
Copy
Edit
git branch -a
Checkout a feature branch:
bash
Copy
Edit
git checkout -b feature/my-task dev
After changes, push the branch:
bash
Copy
Edit
git add .
git commit -m "Add feature"
git push origin feature/my-task
Create a pull request on GitHub to merge into dev.
🌿 Branches Used
Branch	Purpose
main	Stable, production-ready code
dev	Integration branch for tested features
feature/*	Individual features or tasks under dev
🏷️ Tags
Tag	Description
v1.0	Initial stable release
To create a tag:
bash
Copy
Edit
git tag tag1 "Initial release"
git push origin tag1
📁 Project Structure
Copy
Edit
.
├── .gitignore
├── README.md
├── script.sh
└── Dockerfile
🧠 Git Best Practices Followed
Clear commit messages
Feature branches for isolated development
Pull Requests for all merges
.gitignore to avoid unnecessary files
Semantic versioning using tags
Markdown for documentation
👨‍💻 Author
Jaswanth Bavi
