# 📄 Automated Resume Analyzer

> **Status:** ✅ Completed

An AI-powered web application that evaluates a candidate's resume against a job description (JD). The application analyzes ATS compatibility, identifies missing keywords, highlights strengths and weaknesses, and provides AI-generated suggestions to improve resume quality.

By combining Natural Language Processing (NLP), Prompt Engineering, and Google's Gemini API, the project helps job seekers optimize their resumes for Applicant Tracking Systems (ATS) before applying for jobs.

---

# 🎯 Problem Statement

Many organizations use Applicant Tracking Systems (ATS) to automatically filter resumes before they reach recruiters. Even qualified candidates may be rejected because their resumes lack relevant keywords or are not tailored to the job description.

The Automated Resume Analyzer addresses this challenge by comparing a resume with a target Job Description and providing actionable AI-powered feedback that helps users improve their ATS compatibility.

---

# 🚀 Overview

The application allows users to upload their resume in PDF format and provide a target Job Description. It extracts the resume content, compares it with the job requirements using Google's Gemini API, and generates an intelligent analysis that includes:

- ATS Match Score
- Missing Keywords
- Resume Strengths
- Resume Weaknesses
- Profile Summary
- Personalized Improvement Suggestions

The application is built using Streamlit for an interactive user experience while leveraging Generative AI for intelligent resume evaluation.

---

# ✨ Features

- 📄 Upload resumes in PDF format
- 💼 Paste or upload a Job Description
- 🤖 AI-generated ATS Match Score
- 🔍 Missing keyword detection
- 💪 Resume strengths and weaknesses analysis
- 📈 Skill recommendations
- 📝 Profile summary generation
- ⚡ Instant resume analysis
- 🎨 Interactive Streamlit interface

---

# 🛠 Tech Stack

## Frontend

- Streamlit

## Backend

- Python

## AI / NLP

- Google Gemini API
- Prompt Engineering
- Natural Language Processing (NLP)

## Libraries

- streamlit
- google-generativeai
- PyPDF2
- python-dotenv

---

# 🏆 Key Technologies Demonstrated

- Generative AI Integration
- Prompt Engineering
- Natural Language Processing
- PDF Document Processing
- API Integration
- Streamlit Web Application Development
- Environment Variable Management

---

# ⚙️ Project Workflow

1. The user uploads a resume in PDF format.
2. The user provides a Job Description.
3. The application extracts text from the uploaded resume.
4. The resume and Job Description are sent to the Gemini API.
5. Gemini analyzes both documents.
6. The application generates:
   - ATS Match Percentage
   - Missing Keywords
   - Resume Strengths
   - Resume Weaknesses
   - Profile Summary
   - Improvement Suggestions
7. Results are displayed through an interactive Streamlit dashboard.

---

# 🏗 System Architecture

```text
                 Resume (PDF)
                       │
                       ▼
          PDF Text Extraction (PyPDF2)
                       │
                       ▼
               Resume Text
                       │
                       │
Job Description ───────┘
                       │
                       ▼
             Google Gemini API
                       │
                       ▼
      AI Resume & JD Comparative Analysis
                       │
                       ▼
 ┌────────────────────────────────────────┐
 │ • ATS Match Score                      │
 │ • Missing Keywords                     │
 │ • Resume Strengths                     │
 │ • Resume Weaknesses                    │
 │ • Profile Summary                      │
 │ • Improvement Suggestions              │
 └────────────────────────────────────────┘
                       │
                       ▼
          Streamlit Interactive Dashboard
```

---

# 📂 Project Structure

```text
Automated-Resume-Analyzer/
│── app.py
│── requirements.txt
│── .env
│── README.md
│── assets/
│── utils/
└── sample_resume.pdf
```

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Automated-Resume-Analyzer.git
```

Navigate to the project directory:

```bash
cd Automated-Resume-Analyzer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key
```

Run the application:

```bash
streamlit run app.py
```

---

# 💡 Usage

1. Launch the Streamlit application.
2. Upload your resume in PDF format.
3. Paste the target Job Description.
4. Click **Analyze Resume**.
5. Review the generated:
   - ATS Match Score
   - Missing Keywords
   - Profile Summary
   - Strengths & Weaknesses
   - AI Suggestions

---

# 🚧 Challenges Faced

- Extracting clean and readable text from PDF resumes with different layouts.
- Designing prompts that generate consistent ATS evaluations.
- Structuring AI-generated responses into meaningful sections.
- Providing detailed feedback while maintaining fast response times.
- Handling resumes with varying formats and content quality.

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Prompt Engineering
- Integrating Generative AI into real-world applications
- Building interactive applications using Streamlit
- PDF text extraction and preprocessing
- Natural Language Processing concepts
- API integration using Google's Gemini API
- Environment variable management
- Designing AI-assisted user workflows

---

# 🔮 Future Improvements

- Support DOCX resume uploads
- Resume formatting suggestions
- Skill gap visualization dashboard
- Compare multiple resumes
- Downloadable PDF reports
- Job recommendation integration
- Resume history tracking
- Authentication and user accounts

---

# 📸 Screenshots

Add screenshots of the application here.

```text
assets/
├── home.png
├── result.png
└── analysis.png
```

---

# 👩‍💻 Author

**Sunaina**

---

# 📄 License

This project is intended for educational and portfolio purposes.
