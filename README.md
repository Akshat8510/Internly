# 🚀 Internship Recommendation System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Early%20Development-yellow.svg)
![Focus](https://img.shields.io/badge/Field-Machine%20Learning-green.svg)

## 📌 Project Overview
Finding the right internship can be overwhelming. This project aims to build a smart recommendation system that matches students with internship opportunities based on their **skills, interests, and career goals**. 

Currently, the system provides a basic matching framework, which will be evolved into a content-based filtering engine to provide high-accuracy suggestions.

## 🛠️ Tech Stack (Current)
- **Frontend:** HTML5, CSS3 (User Interface)
- **Backend:** Python / Flask (Logic & Routing)
- **Data Handling:** Pandas, NumPy
- **Dataset:** Curated list of internship roles and skill requirements.

## 🚀 Key Features
- **User Profiling:** Users can input their technical skills (e.g., Python, React, Data Analysis).
- **Skill-Based Matching:** The system filters internships that match the user's core competencies.
- **Role Categories:** Categorizes internships into Web Dev, Data Science, Marketing, etc.

## 📈 Evolution Roadmap (Moving to Medium-Level)
To transform this from a simple filter into a **Medium-Level AI project**, the following enhancements are planned:

1. **Content-Based Filtering:** Implementing `TF-IDF Vectorization` and `Cosine Similarity` to recommend internships that are mathematically similar to the user's profile.
2. **Web Scraping:** Using `BeautifulSoup` or `Scrapy` to fetch real-time internship data from platforms like LinkedIn or Internshala.
3. **NLP Integration:** Using Natural Language Processing to parse resume text and extract skills automatically.
4. **Interactive Dashboard:** Moving the UI to `Streamlit` or a React-based frontend for a smoother user experience.

## 📂 Project Structure
```text
├── data/               # Internship datasets (CSV/JSON)
├── static/             # CSS and Images
├── templates/          # HTML files (for Flask)
├── app.py              # Main application logic
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```
## ⚙️ Installation & Usage
1. **Clone the repo:**
   ```bash
   git clone https://github.com/Akshat8510/-Internship-recommendation-system.git
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the app:**
   ```bash
   python app.py
   ```

---
Developed by  [Akshat Kumar](https://github.com/Akshat8510)👍
