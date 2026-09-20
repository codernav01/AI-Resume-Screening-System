# AI Resume Screening System — TF-IDF Candidate Ranking Prototype

> **Applied NLP prototype:** text preprocessing, TF-IDF similarity, structured signals, weighted scoring, and transparent limitations.

## Recruiter Snapshot

| Area | Evidence |
|---|---|
| Language | Python |
| Data | synthetic resumes |
| Text methods | TF-IDF, cosine similarity |
| Structured signals | skills, education, experience |
| Output | ranked candidate list and shortlist export |
| Limitation awareness | no labelled benchmark, fairness study, or calibrated probability |

## Project Objective

This project explores how a lightweight workflow can:

- clean and normalize resume text
- compare resumes with a job description
- detect skill overlap
- extract simple experience signals
- combine multiple scoring components
- rank candidates consistently
- export a shortlist for review

> TF-IDF + cosine similarity is a **lexical similarity baseline**, not a modern semantic embedding model.

## Workflow

```text
Synthetic resumes
      ↓
Text preprocessing
      ↓
Job-description processing
      ↓
TF-IDF representation
      ↓
Cosine similarity
      ↓
Skill / education / experience signals
      ↓
Weighted score
      ↓
Candidate ranking
      ↓
Interactive review / export
```

## Features

- text preprocessing
- TF-IDF vectorization
- cosine-similarity scoring
- skill-overlap detection
- education matching
- regex-based experience extraction
- weighted scoring
- ipywidgets filtering
- shortlist export
- score visualization

## Sample Output

| Candidate | Project score |
|---|---:|
| Priya Sharma | 2.84 |
| Amit Khanna | 1.43 |
| Shruti Shah | 1.42 |

The score is a project-specific ranking value. It is **not** a calibrated probability of candidate quality or hiring success.

## Limitations

- synthetic dataset
- lexical and keyword dependence
- no labelled ground-truth benchmark
- no recruiter-agreement study
- no fairness / subgroup evaluation
- no contextual embedding model
- simplistic regex-based experience extraction

## Responsible Use

This repository is a learning prototype for ranking-system design. It should not be used as an autonomous hiring decision system without proper validation, fairness testing, human review, and governance.

## Repository Structure

```text
AI-Resume-Screening-System/
├── README.md
├── requirements.txt
├── AI-Resume-Screening-System.ipynb
└── synthetic_resumes.csv
```

## Run Locally

1. Install the packages in `requirements.txt`.
2. Launch Jupyter Notebook.
3. Open `AI-Resume-Screening-System.ipynb`.
4. Run the notebook using the included synthetic dataset.

## What This Project Demonstrates

**Text preprocessing, similarity modelling, structured scoring, transparent assumptions, and ranking-workflow design.**
