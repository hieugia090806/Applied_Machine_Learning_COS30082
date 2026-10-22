# 🚀 Applied Machine Learning Unit (COS30082)
> This unit aims to equip students with the essential skills to implement applied machine learning projects. It focuses on techniques and methods used to solve complex real-world problems, rather than on machine learning theories and statistics.

## 🎯 Learning Outcomes:
* Explain machine learning life cycle
* Use appropriate data engineering techniques for data preparation
* Analyse and apply advanced machine learning algorithms to solve complex real-world problems
* Evaluate, deploy and optimise machine learning solutions for given problems
* Interpret and effectively communicate machine learning project outcomes to domain-specific users

## 🌿 Git Branching Strategy:
In terms of maintaining clean code integration and avoid merge conflicts, our repository follows a structured branching model:

* **`main`**: Production-ready code for final submissions and live system demos.
* **`develop`**: Primary integration branch where feature branches are merged.
* **`backend-core`**: Core AI/ML logic, Face Recognition, Liveness Detection, FAISS indexing, and SQLite database.
* **`frontend-gui`**: User interface (Web/Desktop GUI), real-time camera feed processing, and visual attendance status feedback.

> 💡 **Workflow Note:** All feature branches (`backend-core`, `frontend-gui`, or custom feature branches) must be created from `develop` and merged back via Pull Requests (PRs).

```text
Applied_Machine_Learning_COS30082/
├── 📁 Documents/         # Lecture notes, assignment specs, and references
├── 📁 Modules/           # Weekly labs, exercises, and practice code
├── 📁 Project/           # Main project work
│   ├── 📁 Architecture/  # System architecture diagrams and technical spec assets
│   └── 📁 Document/      # Project Proposal, Agile Charter, and Technical Specifications
└── 📄 README.md          # Project documentation and overview
```