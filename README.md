# Final-Project
The final project created by Tily Tu &amp; Yue Qiao

# Table of Contents
- [Project Description](#project-description)
- [Dependencies](#dependencies)
- [Installation & Usage](#installation--usage)
- [Directory Structure](#directory-structure)
- [File Descriptions](#file-descriptions)
- [Reproducing the Experiment](#reproducing-the-experiment)
- [Code Availability](#code-availability)
- [Authors](#authors)
- [License](#license)

---

# Project Description
This project analyzes over 87,000 AI-related patents from PatentsView using topic modeling on patent abstracts to map how U.S. and foreign assignees lead, follow, or lag in machine learning (ML) innovation over time.

# Dependencies
- Python 3.8+  
- Key Python packages (see `requirements.txt`):


# Installation & Usage
1. Clone the repository
 ```bash
 git clone https://github.com/Noddlezip/Final-Project.git
 cd Final-Project
2. 
pip install -r requirements.txt

Final-Project/
├── data/                       # (optional) raw or sample patent data
├── notebooks/                  # Jupyter notebooks
│   ├── Data merging.ipynb: Data loading, cleaning, and merging steps
│   ├── BERTopic.ipynb: Topic modeling pipeline using BERTopic
│   └── Trend analysis.ipynb: Analysis of topic proportions and assignee trajectories
├── report/                     # Final PDF report
│   └── Final Project Tily&Yue.pdf
├── Additional information.pdf  # Team roles
├── requirements.txt            # Python dependencies
└── README.md              
