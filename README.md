# Study of Role-Based Access Control Mechanisms

This repository contains the research, code, and findings for my master's thesis, **"Study of Role-Based Access Control Mechanisms."** The study investigates how different database systems implement **Role-Based Access Control (RBAC)** by comparing their feature sets and measuring the performance of various RBAC operations.

## 📌 Overview

RBAC is a widely used access control model in modern database systems. This thesis aims to:
- Compare the RBAC feature sets across multiple database systems.
- Benchmark the performance of key RBAC operations.
- Identify strengths, limitations, and trade-offs in different implementations.
- Provide insights that can contribute to future database access control designs.

The ultimate goal is to submit a research paper based on these findings to a workshop like **TPCTC (Transaction Processing Performance Council Technology Conference).**

## 📂 Repository Structure

```
📦 study-rbac
 ┣ 📜 README.md            # This file  
 ┣ 📜 thesis.pdf           # The thesis (if public)  
 ┣ 📜 paper-draft.tex      # Research paper draft in LaTeX  
 ┣ 📜 results/             # Benchmark results and logs  
 ┣ 📜 scripts/             # Python/SQL scripts for experiments  
 ┣ 📜 docs/                # Notes and references  
 ┗ 📜 datasets/            # Any datasets used in the study  
```

## 🛠️ Technologies Used

- **Databases:** PostgreSQL, Azure Synapse Analytics, Snowflake, DuckDB  
- **Query Languages:** SQL, Snowflake Scripting  
- **Benchmarking Tools:** Python, SQL scripts, WSL  
- **Document Preparation:** LaTeX  

## 🚀 Getting Started

### Requirements

- Python 3.x  
- PostgreSQL, DuckDB, and other tested database systems installed  
- Required Python packages (listed in `requirements.txt` if applicable)  

### Running Experiments

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/study-rbac.git
   cd study-rbac
   ```  
2. Set up the databases and configure credentials.  
3. Execute the benchmarking scripts:
   ```bash
   python scripts/run_benchmarks.py
   ```  
4. View results in the `results/` folder.  

## 📊 Results & Findings

The results of this study will be continuously updated as experiments progress. Key findings will be summarized in the research paper and thesis.

## 📖 Citation

If you use or reference this work, please cite it as:

> Mads, "Study of Role-Based Access Control Mechanisms," Master's Thesis, 2025.

## 📬 Contact

For any questions or discussions, feel free to open an issue or reach out via GitHub.
