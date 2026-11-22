<div align="center">

<img src="docs/banner.svg" alt="WanderWise AI banner" width="100%"/>

<a href="https://github.com/SyrnaxX/WanderWise-AI">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=FF9E5E&center=true&vCenter=true&width=700&lines=Personalized+destination+recommendations;Tourist+review+sentiment+analysis;Crowd+%26+hotel+price+estimation;Smart+day-wise+itinerary+generation" alt="Typing animation"/>
</a>

<br/>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-ff9e5e?style=for-the-badge)

</div>

---

## 🧭 About

**WanderWise AI** is an AI-powered smart tourism system for personalized destination recommendations, travel planning, tourist analytics and intelligent itinerary generation.

**Initial focus:** India, starting with **Uttarakhand**, with an architecture designed to expand to other states.

## 🚀 Modules & Progress

| # | Module | Techniques | Status |
|---|--------|------------|--------|
| 1 | Destination Recommendation | TF-IDF, Cosine Similarity | 🔜 Planned |
| 2 | **Tourist Sentiment Analysis** | TF-IDF, Linear SVM | ✅ **Completed** |
| 3 | Tourist Crowd Prediction | Random Forest, XGBoost | 🔜 Planned |
| 4 | Hotel Price Estimation | Regression, XGBoost | 🔜 Planned |
| 5 | Travel Budget Estimation | Rule-based + ML | 🔜 Planned |
| 6 | Itinerary Generation | Haversine, Clustering, Greedy | 🔜 Planned |

## 💬 Sentiment Analysis (Completed)

Classifies tourist reviews by sentiment using a text-processing pipeline and a **Linear SVM** model, chosen after comparing candidate models.

| Step | Detail |
|------|--------|
| Text cleaning & tokenization | NLTK / regex |
| Vectorization | TF-IDF |
| Final model | Linear SVM |
| Model files | [`models/Sentiment-Analysis`](models/Sentiment-Analysis) |
| Notebook | [`Notebooks`](Notebooks) |

**Results:** _add your real test-set Accuracy / Precision / Recall / F1 here after checking your notebook._

## 🛠️ Tech Stack

**ML:** Python · Pandas · NumPy · Scikit-learn · XGBoost · NLTK · SHAP  
**Backend:** FastAPI · Pydantic · Docker  
**Frontend:** HTML · CSS · JavaScript  
**Tools:** Kaggle Notebooks · Google Colab · Git & GitHub  
**Deployment (planned):** Vercel (frontend) · Render (backend)

## 🗂️ Repository Structure

```
WanderWise-AI/
├── Notebooks/                 # Kaggle/Colab notebooks
├── models/
│   └── Sentiment-Analysis/    # Trained sentiment model files
├── docs/                      # Banner and documentation assets
├── requirements.txt
├── .gitignore
└── README.md
```

> Planned: `backend/`, `frontend/`, `src/`, `tests/`.

## ⚙️ Getting Started

```bash
git clone https://github.com/SyrnaxX/WanderWise-AI.git
cd WanderWise-AI
pip install -r requirements.txt
```

## 🗺️ Roadmap

- [x] Project setup & repository
- [x] Sentiment analysis model
- [ ] Destination recommendation
- [ ] Crowd prediction
- [ ] Hotel price estimation
- [ ] Budget estimation
- [ ] Itinerary generation
- [ ] FastAPI backend
- [ ] Frontend website
- [ ] Deployment

## 👤 Author

**SyrnaxX** — B.Sc. Computer Science, University of Delhi  
GitHub: [@SyrnaxX](https://github.com/SyrnaxX)

<div align="center">

⭐ *If you like this project, consider giving it a star.*

</div>
