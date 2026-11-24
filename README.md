<div align="center">

<img src="docs/banner.svg" alt="WanderWise AI banner" width="100%"/>

<a href="https://github.com/SyrnaxX/WanderWise-AI">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=FF9E5E&center=true&vCenter=true&width=720&lines=Personalized+destination+recommendations;Tourist+review+sentiment+analysis;Crowd+%26+hotel+price+estimation;Smart+day-wise+itinerary+generation" alt="Typing animation"/>
</a>

<br/>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Planned-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-ff9e5e?style=for-the-badge)
![Progress](https://img.shields.io/badge/Modules-4%20of%206%20done-4c9a6a?style=for-the-badge)

</div>

<img src="docs/divider.svg" width="100%" alt=""/>

## 🧭 About

**WanderWise AI** is an AI-powered smart tourism system for personalized destination recommendations, travel planning, tourist analytics and intelligent itinerary generation.

**Initial focus:** India, starting with **Uttarakhand** — built so other states can be added later.

<img src="docs/divider.svg" width="100%" alt=""/>

## ✨ What WanderWise Will Do

| 🏔️ Discover | 💬 Understand | 📈 Predict |
|---|---|---|
| Personalized destination recommendations | Sentiment analysis of tourist reviews | Crowd levels & hotel price estimates |

| 💰 Budget | 🗓️ Plan |
|---|---|
| Approximate trip cost breakdown | Optimized day-wise itineraries |

<img src="docs/divider.svg" width="100%" alt=""/>

## 🚀 Modules & Progress

| # | Module | Techniques | Status |
|---|--------|------------|--------|
| 1 | **Destination Recommendation** | TF-IDF, Cosine Similarity | ✅ **Completed** |
| 2 | **Tourist Sentiment Analysis** | TF-IDF, Linear SVM | ✅ **Completed** |
| 3 | **Tourist Crowd Prediction** | Random Forest, XGBoost | ✅ **Completed** |
| 4 | **Hotel Price Estimation** | Regression, XGBoost | ✅ **Completed** |
| 5 | Travel Budget Estimation | Rule-based + ML | 🔜 Planned |
| 6 | Itinerary Generation | Haversine, Clustering, Greedy | 🔜 Planned |

<img src="docs/divider.svg" width="100%" alt=""/>

## 🏗️ Architecture (Planned)

```mermaid
flowchart LR
    U[👤 Traveller] --> F[Frontend<br/>HTML · CSS · JS]
    F -->|REST API| B[FastAPI Backend]
    B --> M1[Recommendation ✅]
    B --> M2[Sentiment ✅]
    B --> M3[Crowd & Hotel Price ✅]
    B --> M4[Budget & Itinerary 🔜]
```

## 💬 Sentiment Analysis (Completed)

```mermaid
flowchart LR
    A[Raw reviews] --> B[Text cleaning]
    B --> C[TF-IDF vectors]
    C --> D[Linear SVM]
    D --> E[Positive / Negative / ...]
```

- **Model files:** [`models/Sentiment-Analysis`](models/Sentiment-Analysis)
- **Notebooks:** [`Notebooks`](Notebooks)
- **Results:** _add real test-set Accuracy / Precision / Recall / F1 here from your notebook._

<img src="docs/divider.svg" width="100%" alt=""/>

## 🛠️ Tech Stack

**ML:** Python · Pandas · NumPy · Scikit-learn · XGBoost · NLTK  
**Backend (planned):** FastAPI · Pydantic · Docker  
**Frontend (planned):** HTML · CSS · JavaScript  
**Tools:** Kaggle Notebooks · Google Colab · Git & GitHub  
**Deployment (planned):** Vercel · Render

## 🗂️ Repository Structure

```
WanderWise-AI/
├── Notebooks/                 # Kaggle/Colab notebooks
├── models/
│   └── Sentiment-Analysis/    # Trained sentiment model files
├── docs/                      # README banner & assets
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Getting Started

```bash
git clone https://github.com/SyrnaxX/WanderWise-AI.git
cd WanderWise-AI
pip install -r requirements.txt
```

## 🗺️ Roadmap

- [x] Repository setup
- [x] Destination recommendation
- [x] Sentiment analysis model
- [x] Crowd prediction
- [x] Hotel price estimation
- [ ] Budget estimation
- [ ] Itinerary generation
- [ ] FastAPI backend
- [ ] Frontend website
- [ ] Deployment (Vercel + Render)

<img src="docs/divider.svg" width="100%" alt=""/>

<div align="center">

**SyrnaxX** · B.Sc. Computer Science, University of Delhi  
[GitHub @SyrnaxX](https://github.com/SyrnaxX)

⭐ *If you like this project, consider giving it a star.*

</div>
