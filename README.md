# 🚀 ResumeAI Pro

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.58-FF4B4B?logo=streamlit)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-blue?logo=google)
![AI](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-purple)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Production-success)

</p>

<h3 align="center">
AI-powered Resume Analyzer & Career Assistant
</h3>

<p align="center">

Analyze resumes, optimize ATS compatibility, compare resumes with job descriptions, generate professional cover letters, rewrite resumes, create LinkedIn summaries, receive AI-powered career advice, chat with your resume, and export professional PDF reports using Google Gemini AI.

</p>

<p align="center">

## 🌐 Live Demo

### https://phantommw-resumeai.streamlit.app/

</p>

---

# 📖 Overview

ResumeAI Pro is an AI-powered web application designed to help job seekers improve their resumes using Google's Gemini Large Language Model.

The system analyzes resumes, evaluates ATS compatibility, detects missing skills, measures resume quality, generates professional cover letters, rewrites resumes, provides career guidance, creates LinkedIn summaries, answers resume-related questions, and exports comprehensive PDF reports.

The project combines Artificial Intelligence with an interactive Streamlit interface to create a complete career assistant.

---

# 📸 Application Preview

## 🏠 Home Page

<p align="center">
<img src="assets/screenshots/home.png" width="100%">
</p>

---

## 📄 Upload Resume

<p align="center">
<img src="assets/screenshots/Upload.png" width="100%">
</p>

---

## 📊 Resume Dashboard

<p align="center">
<img src="assets/screenshots/Dashboard.png" width="100%">
</p>

---

## 🧠 Skills Analysis

<p align="center">
<img src="assets/screenshots/Skills.png" width="100%">
</p>

---

## 📈 Interactive Charts

<p align="center">
<img src="assets/screenshots/Charts.png" width="100%">
</p>

---

## 💌 AI Cover Letter Generator

<p align="center">
<img src="assets/screenshots/Cover_Letter.png" width="100%">
</p>

---

## ✨ Resume Rewriter

<p align="center">
<img src="assets/screenshots/Rewrite.png" width="100%">
</p>

---

## 💼 Career Advisor

<p align="center">
<img src="assets/screenshots/Career.png" width="100%">
</p>

---

## 🤖 Resume AI Chat

<p align="center">
<img src="assets/screenshots/AI_ask.png" width="100%">
</p>

---

# ✨ Key Features

| Feature | Description |
|----------|-------------|
| 📄 Resume Analysis | Comprehensive AI-powered resume evaluation |
| 🎯 ATS Compatibility | ATS score and optimization suggestions |
| 📈 Resume Quality Score | Professional quality assessment |
| 💼 Job Match Analysis | Compare resume with job descriptions |
| 🧠 Skills Detection | Hard & Soft Skills identification |
| ⚠️ Missing Skills | Detect missing requirements |
| 💌 Cover Letter Generator | AI-generated professional cover letters |
| ✨ Resume Rewriter | ATS-optimized resume rewriting |
| 👔 LinkedIn Summary | Generate LinkedIn About section |
| 🚀 Career Advisor | Personalized career recommendations |
| 🤖 Resume AI Chat | Interactive AI assistant |
| 📑 PDF Report | Professional downloadable report |
| 🕒 Analysis History | Save previous analyses |

---

# 🛠️ Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python 3.11 |
| Framework | Streamlit |
| AI Model | Google Gemini 2.5 Flash |
| Data Visualization | Plotly |
| PDF Parsing | PDFPlumber |
| DOCX Parsing | python-docx |
| PDF Generation | ReportLab |
| Environment | python-dotenv |

---

# 📂 Project Structure

```text
ResumeAI-Pro/

├── assets/
│   └── screenshots/

├── components/
│   ├── charts.py
│   ├── dashboard.py
│   ├── decision.py
│   ├── interview.py
│   ├── metrics.py
│   ├── reviews.py
│   └── skills.py

├── images/

├── analyzer.py
├── app.py
├── career_advisor.py
├── config.py
├── cover_letter.py
├── gemini_client.py
├── history.py
├── history.json
├── linkedin_summary.py
├── parser.py
├── prompts.py
├── report.py
├── requirements.txt
├── results.py
├── resume_chat.py
├── rewrite.py
├── ui.py
├── utils.py

└── README.md
```
---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/PhantomMW/ResumeAI-Pro.git
```

---

## 2️⃣ Navigate to the Project Folder

```bash
cd ResumeAI-Pro
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Create a `.env` File

Create a file named `.env` in the project root and add:

```env
GEMINI_API_KEY=YOUR_API_KEY
```

---

## 5️⃣ Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```
http://localhost:8501
```

---

# 🚀 Live Demo

### 🌐 Streamlit Cloud

➡️ https://phantommw-resumeai.streamlit.app/

---

# 🤖 AI Capabilities

ResumeAI Pro leverages **Google Gemini 2.5 Flash** to provide intelligent resume analysis and career assistance.

| Capability | Description |
|------------|-------------|
| 📄 Resume Analysis | Analyze resume content professionally |
| 🎯 ATS Evaluation | ATS compatibility scoring |
| 📈 Resume Quality | Overall resume quality assessment |
| 💼 Job Matching | Compare resume with job description |
| 🧠 Skills Detection | Detect hard & soft skills |
| ⚠️ Missing Skills | Identify missing technologies and skills |
| 💌 Cover Letter | Generate personalized cover letters |
| ✨ Resume Rewriter | Rewrite resumes professionally |
| 👔 LinkedIn Summary | Generate LinkedIn About section |
| 🚀 Career Advisor | Personalized AI career guidance |
| 🤖 Resume Chat | Ask questions about your resume |
| 📑 PDF Report | Export professional reports |

---

# 📊 System Workflow

```text
                     User
                       │
                       ▼
               Upload Resume
                       │
                       ▼
              Resume Parser
                       │
                       ▼
             Google Gemini AI
                       │
      ┌────────────────┼────────────────┐
      ▼                ▼                ▼
 ATS Analysis   Resume Analysis   Career Analysis
      │                │                │
      └────────────────┼────────────────┘
                       ▼
          Interactive Dashboard
                       │
      ┌────────────────┼────────────────┐
      ▼                ▼                ▼
 Cover Letter   Resume Rewrite   Resume Chat
                       │
                       ▼
               PDF Report Export
```

---

# 📦 Application Modules

| Module | Purpose |
|---------|---------|
| Resume Parser | Extract text from PDF/DOCX |
| Resume Analyzer | AI resume evaluation |
| ATS Checker | ATS compatibility |
| Dashboard | Resume analytics |
| Skills Analyzer | Skills detection |
| Charts | Interactive visualization |
| Resume Rewriter | Resume optimization |
| Cover Letter Generator | AI cover letters |
| LinkedIn Generator | LinkedIn summary |
| Career Advisor | Career recommendations |
| Resume Chat | AI assistant |
| PDF Report | Export analysis |
| History | Store previous analyses |

---

# 🎯 Future Improvements

- 🔐 User Authentication
- ☁️ Cloud Database
- 🌍 Multi-language Support
- 🎤 AI Mock Interviews
- 📁 Portfolio Analysis
- 🔗 LinkedIn Resume Import
- 📊 Resume Version Comparison
- 🏢 Company-specific ATS Optimization
- 📄 Professional Resume Templates
- 📱 Mobile Responsive UI
- 📧 Email Report Sharing
- 🧠 AI Interview Coach

---

# 👨‍💻 Developer

<div align="center">

# Mohammed Wael

### 🤖 AI Developer | ⚙️ Mechatronics Engineer

Passionate about building intelligent software that combines Artificial Intelligence, Automation, Robotics, and Mechatronics Engineering to solve real-world problems.

</div>

---

# 🛠 Skills

- Python
- Artificial Intelligence
- Machine Learning
- Google Gemini AI
- Streamlit
- Data Analysis
- Automation
- Robotics
- Embedded Systems
- Mechatronics Engineering

---

# 📬 Connect With Me

### GitHub

https://github.com/PhantomMW

### Live Demo

https://phantommw-resumeai.streamlit.app/

---

# ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub.

It really helps and motivates future development.

---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project under the terms of the MIT License.

---

<div align="center">

# 🚀 ResumeAI Pro

### Developed with ❤️ by Mohammed Wael

### 🤖 AI Developer | ⚙️ Mechatronics Engineer

© 2026 Mohammed Wael. All Rights Reserved.

</div>
