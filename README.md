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
![image alt](https://github.com/jaswanthBavi/devops-git-workflow/blob/814648ebb03c05868e8d4b98ce81161792fb3577/Screenshot%202025-04-11%20121022.png)
![image alt](https://github.com/jaswanthBavi/devops-git-workflow/blob/52b5ddcec4599caec431d4353f9aa26ad380b8f9/Screenshot%202025-04-11%20121133.png)
![image alt](https://github.com/jaswanthBavi/devops-git-workflow/blob/c97e149a56b02971a90f2495b1c03d34d98f8e52/Screenshot%202025-04-11%20121413.png)
![image alt](https://github.com/jaswanthBavi/devops-git-workflow/blob/8c09e0562d932f0c1fa0f17d3b03d8eb93a17dfd/Screenshot%202025-04-11%20121745.png)
