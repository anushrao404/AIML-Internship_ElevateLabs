# 🤖 AI-Powered Resume Ranker

> Effortlessly rank and shortlist resumes using Natural Language Processing (NLP) techniques — accurate, scalable, and built for recruiters.

---

## 🚀 Project Overview

The **AI-Powered Resume Ranker** is a smart application that automatically evaluates and ranks candidate resumes based on their relevance to a given job description using advanced NLP methods. Designed for HR teams and recruiters to **save time** and **enhance hiring accuracy**.

---

## 🔍 Features

- 📄 Extract text from PDF resumes
- 🧠 Preprocess content using SpaCy
- 📊 Vectorize using TF-IDF
- 🎯 Score and rank resumes out of **1000**
- 💼 Match resumes against **any custom Job Description (JD)**
- 📥 Export final results as a downloadable CSV report
- ✅ Ready-to-run in Google Colab — no server setup needed!

---

## 🛠 Tech Stack

| Tool        | Purpose                        |
|-------------|--------------------------------|
| Python      | Core programming language      |
| SpaCy       | NLP preprocessing              |
| Scikit-learn| TF-IDF & Cosine Similarity     |
| PyPDF2      | Extracting text from PDFs      |
| Pandas      | Data manipulation              |
| Google Colab| Development environment        |

---
## 📌 How It Works

1. **Upload resumes** (PDF format) in Colab
2. **Input job description** (e.g., Full Stack Developer)
3. **Preprocessing & Vectorization**
4. **Cosine similarity** used to rank candidates
5. **Download results** as a report

---

## 📌 Project Highlights

| Feature                      | Description                                                                                  |
|-----------------------------|----------------------------------------------------------------------------------------------|
| 📄 PDF Resume Extraction    | Supports batch uploading of candidate resumes in `.pdf` format                              |
| 🧠 NLP Preprocessing         | Cleans, tokenizes, and lemmatizes resume content using `spaCy`                               |
| 🔍 Intelligent Matching      | Matches resumes to job descriptions using **TF-IDF + Cosine Similarity**                     |
| 📈 Scoring System            | Assigns scores out of **100** for clear candidate ranking                                   |
| 💼 Flexible Job Roles        | Easily swap in JDs for Full Stack, Data Scientist, DevOps, and more                          |
| 🌐 Web Interface (Flask)     | Upload resumes, input JD, view results, and download HR reports — all from one UI            |
| 📤 Downloadable HR Reports   | Export ranked results as `.csv` for easy tracking and sharing                                |


## 💻 Run on Google Colab

> Click the badge below to launch:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

### ✅ Steps:
1. Upload your PDF resumes when prompted
2. Paste the job description for the open role
3. Run the notebook cells one by one
4. Download the final CSV score sheet

---

## 🧪 Sample Output

| Rank | Resume           | Score (/100) |
|------|------------------|----------------|
| 1    | JohnDoe.pdf      | 89            |
| 2    | JaneSmith.pdf    | 74            |
| 3    | NewGrad.pdf      | 98            |

---

## 📥 Sample Job Descriptions 

### ✅ Full Stack Developer  
Seeking a Full Stack Developer skilled in React, Node.js, REST APIs, and MongoDB.  
Must have experience building scalable web apps with both frontend and backend technologies.

### ✅ Data Scientist  
Looking for a Data Scientist with expertise in Python, Pandas, Scikit-learn, and machine learning.  
Experience in data analysis, model building, and visualization is required.

### ✅ Backend Developer  
Hiring a Backend Developer proficient in Node.js, Express.js, RESTful APIs, and database design.  
Should be experienced in building scalable server-side applications.

### ✅ Frontend Developer  
We need a Frontend Developer with strong skills in HTML, CSS, JavaScript, and React.js.  
Must have experience creating responsive and user-friendly interfaces.

### ✅ DevOps Engineer  
Seeking a DevOps Engineer familiar with CI/CD, Docker, Kubernetes, and cloud platforms like AWS.  
Should have experience automating deployments and managing infrastructure.

---

## 📌 Future Improvements

- ✅ Web UI with Flask or Streamlit
- 📄 PDF HR Summary Report
- 🌐 Multi-language support
- 🔍 Keyword highlighting in resumes

---

## 🤝 Contributing

Contributions are welcome! If you'd like to:
- Add features
- Report bugs
- Suggest enhancements

Feel free to open issues or submit pull requests.

---
---

## 📞 Contact & Support

If you have any questions, suggestions, or would like to discuss the project further, please feel free to reach out. I'm open to collaboration, feedback, or simply helping others understand and use this tool effectively.

You can connect with me through the following platforms:

- 📧 **Email**: [Email me!](mailto:teermanwaranush@gmail.com)  
- 💼 **LinkedIn**: [Find Me here!!](https://www.linkedin.com/in/anushrao/)  
- 🐙 **GitHub**: [Click Me..](https://github.com/anushrao404/)

I appreciate your interest in this project. If you find it useful, a ⭐ on the repository would mean a lot!



