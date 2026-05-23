#  AI-Powered Resume Screening System using NLP & TF-IDF

An intelligent Resume Screening System built using **Natural Language Processing (NLP)** and **TF-IDF-based semantic similarity** to automate candidate shortlisting and improve recruitment efficiency.

This project helps recruiters identify the most relevant candidates by comparing resumes with a given Job Description (JD) using multiple scoring parameters such as skills, education, experience, and contextual similarity.

---

#  Project Objective

Manual resume screening is time-consuming, repetitive, and often inconsistent.

The goal of this project is to build an AI-assisted screening pipeline that:
- Reduces manual effort
- Improves candidate matching accuracy
- Ranks resumes automatically
- Makes hiring workflows faster and more scalable

---

#  Features

- ✅ Resume preprocessing and text cleaning
- ✅ TF-IDF based semantic similarity matching
- ✅ Skill overlap detection
- ✅ Education matching
- ✅ Experience extraction using regex
- ✅ Weighted candidate ranking system
- ✅ Interactive filtering dashboard
- ✅ Candidate shortlist export to CSV
- ✅ Resume scoring visualization

---

# 🛠️ Technologies Used

| Category | Tools & Libraries |
|---|---|
| Programming Language | Python |
| Data Handling | Pandas |
| NLP | TF-IDF Vectorizer |
| Similarity Calculation | Cosine Similarity |
| Visualization | Matplotlib |
| Interactive UI | ipywidgets |
| Notebook Environment | Jupyter Notebook |

---

#  Dataset Information

The project uses a synthetic dataset containing multiple candidate resumes.

### Dataset Fields:
- Name
- Email
- Phone
- Summary
- Skills
- Education
- Experience
- Projects
- Certifications

---

# ⚙️ Project Workflow

## 1️⃣ Data Loading
- Imported resume dataset from CSV format
- Loaded resumes into Pandas DataFrame

## 2️⃣ Data Preprocessing
- Removed unnecessary symbols and formatting
- Combined important resume sections
- Converted text into machine-readable format

## 3️⃣ Job Description Parsing
- Extracted required skills and qualifications from JD

## 4️⃣ Semantic Similarity Matching
- Applied TF-IDF Vectorization
- Calculated cosine similarity between resumes and JD

## 5️⃣ Resume Scoring
Candidates were evaluated based on:
- Skill Match
- Education Match
- Experience Relevance
- Semantic Similarity

## 6️⃣ Candidate Ranking
- Generated final weighted scores
- Ranked candidates from highest to lowest relevance

## 7️⃣ Interactive Dashboard
Users can:
- Filter candidates
- Search profiles
- Analyze rankings
- Export shortlisted resumes

---

# 📊 Sample Output

| Candidate Name | Final Score |
|---|---|
| Priya Sharma | 2.84 |
| Amit Khanna | 1.43 |
| Shruti Shah | 1.42 |

---

# 📈 Key Learning Outcomes

Through this project, I gained hands-on experience in:
- NLP fundamentals
- TF-IDF Vectorization
- Cosine Similarity
- Resume parsing logic
- Text preprocessing
- Interactive dashboard creation
- Candidate ranking systems
- End-to-end ML workflow design

---

# 💡 Future Improvements

- Integrating BERT/Sentence Transformers
- PDF Resume Parsing
- Streamlit Web Application Deployment
- Real-time Recruiter Dashboard
- OCR Support for Scanned Resumes
- AI-based Candidate Recommendations

---

# ▶️ How to Run the Project

## Step 1: Clone Repository
```bash
git clone https://github.com/codernav01/AI-Resume-Screening-System.git
```

## Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

## Step 3: Launch Jupyter Notebook
```bash
jupyter notebook
```

## Step 4: Open Notebook
```bash
Resume-Screening-System.ipynb
```

---

#  Project Output

- Ranked Resume List
- Candidate Similarity Scores
- Interactive Dashboard
- Downloadable Shortlist CSV
- Resume Matching Insights

---

# 📌 Conclusion

This project demonstrates how AI and NLP techniques can streamline modern recruitment workflows by automating resume analysis and candidate ranking.

By combining TF-IDF, cosine similarity, and structured scoring mechanisms, the system helps recruiters identify the most suitable candidates in a faster, smarter, and more objective way.

---
