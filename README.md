# 404-Librarian-Not-Found ( It’s AI Now )
The project is setup as a Kaggle competition, but this is only one aspect of the full project. You should also develop an independent application using Streamlit, where you use your predictive model and showcase your solution.

(3 people per team) Your report is your README.md of your github page. It should contain your results, your rank in the competition, your UI/demo, and a video where you showcase your solution (no need to show code).

## Evaluation:
- Kaggle Rank
- Code quality (using classes, splitting into proper files, documentation, etc)
- User interface and application that you create based on the model (use streamlit for that)
- Github quality (include link to video, table with progress over time, organization of code, images, etc)
- Presentation / Video quality (good slides, interesting presentation).

# 📚 The Lazy Librarian
> _“An AI-powered assistant that recommends books so librarians can finally take a break!”_

---

## 🧠 Overview

**The Lazy Librarian** is a book recommendation system built for the Kaggle challenge.  
It combines **collaborative filtering** and **transformer-based NLP** to suggest books that match user preferences.

🎯 Goal: Automate personalized book recommendations for university students.

---

## 🚀 Tech Stack

| Category | Tools Used |
|-----------|-------------|
| Programming | Python 3.11 |
| Data Science | Pandas, NumPy, Scikit-learn |
| Recommender System | LightFM, Surprise, NCF |
| NLP | Sentence-BERT |
| Visualization | Matplotlib, Seaborn |
| Frontend | Streamlit |
| Version Control | Git + GitHub Projects |

---

## 🗓️ Project Progress

| Date | Milestone | Description | Status |
|------|------------|-------------|---------|
| Oct 15 | 📂 Setup | Created repo and initialized project structure | ✅ Done |
| Oct 20 | 🧹 Data Cleaning | Processed and merged dataset | ✅ Done |
| Oct 25 | 🤖 Model Training | Trained baseline + deep learning model | 🚧 In Progress |
| Nov 05 | 💻 Streamlit UI | Built a demo interface for recommendations | 🔜 Planned |
| Nov 10 | 🎥 Presentation | Recorded final video and slides | 🔜 Planned |

🗂️ [View detailed progress board →](https://github.com/YourUsername/TheLazyLibrarian/projects)

---

## 🧩 System Architecture

```mermaid
graph TD
A[User Input] --> B[Data Preprocessing]
B --> C[Recommendation Engine]
C --> D[Streamlit UI]
D --> E[Book Suggestions]
