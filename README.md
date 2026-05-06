# 📄 AI Resume Analyzer

**AI Resume Analyzer** is a web-based application that analyzes and ranks resumes based on their relevance to a given job description using Natural Language Processing (NLP) techniques.
The project is built using **Python, Flask, Scikit-learn, HTML, CSS, and JavaScript**.

The system uses **TF-IDF Vectorization** and **Cosine Similarity** to compare resumes with job descriptions and identify the most relevant candidates.

---

## 🚀 Features

* Upload multiple resumes for analysis
* Supports `.pdf`, `.docx`, and `.txt` resume formats
* Job description matching using NLP techniques
* Resume ranking based on similarity score
* Displays top matching resumes
* Clean and responsive user interface
* Easy deployment on platforms like Render and Railway

---

## 🖥️ Application Interface

![App Interface](https://github.com/SeekAI-786/Resume-Analyzer/blob/main/r2.png)

---

![App Interface](https://github.com/SeekAI-786/Resume-Analyzer/blob/main/r1.png)

---

## ⚙️ How It Works

1. User uploads resumes and enters a job description.
2. The system extracts text from uploaded resumes:

   * PDF → PyPDF2
   * DOCX → docx2txt
   * TXT → Standard file reader
3. Text is processed using **TF-IDF Vectorizer**.
4. Cosine similarity is calculated between resumes and the job description.
5. Resumes are ranked based on similarity score.
6. Top matching resumes are displayed to the user.

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Python Flask
* **Machine Learning:** Scikit-learn
* **NLP Techniques:** TF-IDF Vectorization, Cosine Similarity
* **File Processing:** PyPDF2, docx2txt

---

## 📁 Supported File Formats

* PDF (`.pdf`)
* Word Documents (`.docx`)
* Text Files (`.txt`)

---

## ▶️ Installation & Setup

### 1. Clone Repository

```bash id="e9v2pk"
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer
```

---

### 2. Install Dependencies

```bash id="r5m8xn"
pip install -r requirements.txt
```

---

### 3. Run Application

```bash id="f2t4qa"
python main.py
```

---

### 4. Open in Browser

```bash id="k7v1rm"
http://localhost:5000
```

---

## 🌐 Deployment

The project can be deployed on:

* Render
* Railway
* PythonAnywhere
* Heroku

---

## 🔮 Future Improvements

* AI-powered resume suggestions
* Deep learning-based semantic matching
* ATS score prediction
* Resume keyword optimization
* Recruiter dashboard and analytics

---

## 👨‍💻 Author

**Anmol Kankarwal**
B.Tech CSE (AI) Student
Galgotias University

* GitHub: https://github.com/Anmolkankarwal

---
