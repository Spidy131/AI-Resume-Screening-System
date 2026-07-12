# 🤖 AI Resume Screening System

An AI-powered Resume Screening System that compares resumes with job descriptions using semantic similarity and Google's Gemini AI.

## 🌐 Live Demo

🔗 **Try the application here:**

https://ai-resume-screening-system-jka2xffmzwjvma5jhgnaky.streamlit.app/

---

## 🚀 Features

- 📄 Upload Resume (PDF)
- 📋 Upload Job Description (PDF)
- 🧠 Semantic Resume Matching using Sentence Transformers
- 📊 ATS Resume Match Score
- 🤖 AI-powered Resume Analysis using Gemini
- ✅ Matching Skills
- ❌ Missing Skills
- 💪 Strengths & Weaknesses
- 🎓 Education & Experience Match
- ⭐ Hiring Recommendation
- ❓ AI-generated Interview Questions

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Google Gemini API
- Sentence Transformers
- FAISS
- PyMuPDF
- NumPy
- Pandas
- Scikit-learn
- Transformers
- Torch

---

## 📂 Project Structure

```text
AI-Resume-Screening-System/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── .streamlit/
    └── secrets.toml (Not uploaded)
```

---

## ⚙️ Installation

```bash
git clone https://github.com/Spidy131/AI-Resume-Screening-System.git

cd AI-Resume-Screening-System

pip install -r requirements.txt

streamlit run app.py
```

---

## 🔑 Configure Gemini API

Create:

```text
.streamlit/secrets.toml
```

Add:

```toml
GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
```

---

## 📈 Future Improvements

- Multiple resume screening
- Resume ranking
- Export ATS report to PDF
- Support DOCX resumes
- Batch resume processing

---

## 👨‍💻 Author

**Sachin Malode**

- GitHub: https://github.com/Spidy131
- Live App: https://ai-resume-screening-system-jka2xffmzwjvma5jhgnaky.streamlit.app/

If you found this project useful, consider giving it a ⭐ on GitHub!
