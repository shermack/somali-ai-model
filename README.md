# SOMALI AI MODEL

Welcome to our project! This repository contains all the source code, workflows, and documentation for our collaborative development.  

---

## 📌 Overview  
This project is structured with **collaboration, scalability, and automation** in mind. We are using:  
- **GitHub** for version control, branching, and CI/CD.  
- **Notion** as our knowledge base and documentation hub.  
- **Trello** for task management and Kanban tracking.  
- **GitHub Actions** for automation (tests, linting, training workflows, docs).  

---

## 📂 Repository Structure  

.
├── data/                # Datasets & preprocessing scripts  
├── models/              # Model training & saved weights  
├── notebooks/           # Jupyter notebooks for experimentation  
├── src/                 # Core source code  
├── tests/               # Unit and integration tests  
├── docs/                # Documentation (MkDocs/Sphinx)  
└── .github/workflows/   # CI/CD workflows 


---

## 🌿 Branching Strategy  

We use **GitHub Flow** with clear roles:  

- **`main`** → production-ready & stable.  
- **`dev`** → integration branch for development.  
- **`feature/*`** → each feature has its own branch (merged into `dev`).  

Example workflow:  

```bash
git checkout dev
git checkout -b feature/data-pipeline
# work on changes
git add .
git commit -m "Added initial data pipeline"
git push -u origin feature/data-pipeline

⚡ GitHub Actions (CI/CD)

Automation is built into our workflow:

    ✅ Testing → Runs pytest on every PR.

    🧹 Linting & Formatting → flake8 + black to enforce clean code.

    🤖 Model Training → Automated model training workflows.

    📖 Documentation Build → Auto-deploy docs using MkDocs/Sphinx.

📋 Project Management

    📝 Notion → Documentation, research notes, and meeting summaries.

    📌 Trello → Task board (To Do → In Progress → Review → Done).

    🔗 GitHub Issues & PRs → Linked with Trello for transparency.
