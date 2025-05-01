# 🧠 Resume Analyzer ATS – Powered by Gemini & Python

🎯 **Your AI-Powered Resume Sidekick for Beating the Bots!**

Welcome to **Resume Analyzer ATS**, an intelligent tool built to help job seekers stand out in the hiring process by *analyzing resumes like an Applicant Tracking System (ATS)*. Whether you're applying for your dream job or fine-tuning your CV, this project gives you smart insights that real hiring bots look for.

---

## 🚀 What This Does

This Python-based analyzer, enhanced with **Google's Gemini AI**, compares your resume against a given job description and gives you:

✅ **ATS Resume Score** (Match % based on relevance)  
🔑 **Missing Keywords** (Skills, tools, or experiences not mentioned)  
📊 **Smart Suggestions** to improve your resume  
🖼️ **PDF Preview using pdf2image**  
🌐 **Interactive Streamlit UI** for ease of use  
📁 **Support for PDF Resume Format**

---

## 💡 Why This Matters

Most resumes are **screened by AI systems (ATS)** before a human even looks at them. This tool helps you:

- **Understand how well your resume matches the job description**
- **Identify important keywords you're missing**
- **Optimize your resume for higher shortlisting chances**

Perfect for **students, job seekers, career coaches**, or **resume-enhancing platforms**.

---

## 🔧 Built With

- 🐍 Python 3  
- 🌐 Streamlit – for interactive web interface  
- 🧠 Gemini API – for intelligent, contextual comparison  
- 📄 `pdf2image` – to render resume preview 

---

## 🛠️ How to Clone and Run

```bash
# 1. Clone the repository
git clone https://github.com/AKill-17/Resume-analyzer.git
cd Resume-analyzer

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install the dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
