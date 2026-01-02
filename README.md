# 🚀 Internly - AI-Powered Internship Discovery

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Active%20Development-green.svg)
![AI/ML](https://img.shields.io/badge/Algorithm-Content--Based%20Filtering-orange.svg)

**Internly** is an intelligent recommendation engine designed to bridge the gap between student skills and career-launching opportunities. No more endless scrolling through irrelevant listings—Internly uses data to find where you truly belong.

## 📌 Project Overview
The core challenge for students today isn't a lack of internships, but a "noise" problem. Internly solves this by building a mathematical profile of a user's skills and matching it against a curated database of roles using Machine Learning.

## ✨ Key Features
- **Smart Profiling:** Custom user input for technical stacks (Python, React, SQL, etc.).
- **Relevance Scoring:** (In Development) Provides a match percentage for every internship.
- **Categorized Discovery:** Instant filtering by domains like Software Engineering, Data Science, and UI/UX.
- **Minimalist UI:** Clean, distraction-free interface for quick discovery.

## 🛠️ Tech Stack
- **Backend:** Python (Flask)
- **Data Science:** Pandas, NumPy, Scikit-Learn
- **Frontend:** HTML5, CSS3, JavaScript
- **Vectorization:** TF-IDF (Term Frequency-Inverse Document Frequency)

## 📈 The Roadmap to "Elite" Level
Internly is currently evolving from a basic filtering tool into a high-signal AI platform:

1.  **Phase 1 (Current):** Basic skill-to-role matching and user interface.
2.  **Phase 2 (Next):** Implementing `Cosine Similarity` to calculate the mathematical distance between a student's resume and a job description.
3.  **Phase 3:** Automated web-scraping to keep the internship database fresh and live.
4.  **Phase 4:** Sentiment analysis on job descriptions to identify "Company Culture" fit.

## 📂 Project Structure
```text
├── data/               # Internship datasets (CSV/JSON)
├── static/             # CSS, JS, and Branding Assets
├── templates/          # Flask HTML templates
├── app.py              # Main logic & recommendation engine
├── requirements.txt    # Essential libraries
└── README.md           # Documentation
```

## ⚙️ Setup & Installation
To run Internly locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Akshat8510/Internly.git
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch the platform:**
   ```bash
   python app.py
   ```

---
*Developed with ❤️ by [Akshat](https://github.com/Akshat8510) — Making the internship search smarter, one vector at a time.*
