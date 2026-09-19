# AI Resume Screening System — TF-IDF Candidate Ranking

## Project Overview

This project builds a **rule-assisted resume ranking workflow** using Python, text preprocessing, TF-IDF, cosine similarity, and structured scoring.

The system compares synthetic resumes against a job description and produces a ranked candidate list using multiple signals such as skills, education, experience, and **lexical text similarity**.

> TF-IDF + cosine similarity is used here as a text-similarity baseline. It should not be interpreted as a modern embedding-based semantic model.

## Objective

The project explores how a lightweight automated workflow can:

- preprocess resume text
- compare resumes with a job description
- detect skill overlap
- extract simple experience signals
- combine multiple scoring components
- rank candidates consistently
- export a shortlist for review

The project demonstrates a ranking workflow; it does **not** claim validated improvements in hiring accuracy without a labelled benchmark or human-evaluation study.

## Features

- resume preprocessing and cleaning
- TF-IDF vectorization
- cosine-similarity scoring
- skill overlap detection
- education matching
- regex-based experience extraction
- weighted candidate scoring
- interactive filtering with ipywidgets
- shortlist export
- score visualization

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data handling | Pandas |
| Text representation | TF-IDF Vectorizer |
| Similarity | Cosine Similarity |
| Visualization | Matplotlib |
| Interactive controls | ipywidgets |
| Environment | Jupyter Notebook |

## Dataset

The repository uses a **synthetic resume dataset** with fields such as:

- Name
- Email
- Phone
- Summary
- Skills
- Education
- Experience
- Projects
- Certifications

Because the data is synthetic, the project is best viewed as a workflow prototype rather than a validated production hiring system.

## Workflow

```text
Synthetic resumes
      ↓
Text cleaning / preprocessing
      ↓
Job-description processing
      ↓
TF-IDF representation
      ↓
Cosine similarity
      ↓
Structured skill / education / experience signals
      ↓
Weighted score
      ↓
Candidate ranking
      ↓
Interactive review / CSV export
```

## Sample Output

| Candidate | Final Score |
|---|---:|
| Priya Sharma | 2.84 |
| Amit Khanna | 1.43 |
| Shruti Shah | 1.42 |

The score is a project-specific ranking value, not a calibrated probability of candidate quality or hiring success.

## Limitations

- synthetic dataset
- keyword and lexical dependence
- no labelled ground-truth benchmark
- no recruiter agreement study
- no fairness / bias evaluation
- no contextual embedding model
- regex-based experience extraction is simplistic

## Future Improvements

- Sentence Transformers or other embedding models
- PDF resume parsing
- Streamlit deployment
- labelled evaluation dataset
- recruiter agreement metrics
- fairness and subgroup analysis
- calibration of ranking weights
- explainable score breakdowns

## How to Run

1. Clone the repository.
2. Install the libraries used in the notebook, such as Pandas, scikit-learn, Matplotlib, Jupyter, and ipywidgets.
3. Launch Jupyter Notebook.
4. Open `AI-Resume-Screening-System.ipynb`.

## What This Project Demonstrates

This project demonstrates **text preprocessing, similarity modelling, structured scoring, and ranking-system design** while making the limits of a TF-IDF prototype explicit.
