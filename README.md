<!-- PROJECT HEADER -->
<p align="center">
  <img width="1536" height="1024" alt="4ecd1b2a-0b59-4f8c-b82d-7c232701f924" src="https://github.com/user-attachments/assets/80bab2d7-4e99-46e6-8a42-6469ef448ea0" />

</p>

<h1 align="center">🛰️ Winning the Space Race with Data Science</h1>

<p align="center">
  <em>Predicting SpaceX Falcon 9 rocket landing success through data-driven analytics, machine learning, and storytelling.</em>
</p>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python"></a>
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/Machine%20Learning-ScikitLearn%20%7C%20XGBoost-orange?logo=scikit-learn"></a>
  <a href="https://dash.plotly.com/"><img src="https://img.shields.io/badge/Dashboard-Plotly%20Dash%20%7C%20Folium-lightblue?logo=plotly"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg"></a>
  <a href="https://github.com/AaronKGoldman/Data-Science-Capstone-IBM"><img src="https://img.shields.io/badge/Open%20in-GitHub-black?logo=github"></a>
</p>

---

## 🚀 Project Overview

**Winning the Space Race with Data Science** is a **portfolio-grade, consulting-style analytics project** demonstrating how a data analyst can apply **Python, SQL, and Machine Learning** to predict **SpaceX Falcon 9 rocket landing success** and quantify **cost savings through reusability**.  

> 🎯 *Business Impact:* $100M+ potential cost optimization through predictive modeling  
> 📈 *Model Accuracy:* 86.7% (Decision Tree Classifier)  
> 🧭 *Mission:* Transform aerospace analytics into actionable, executive insights  

---


---
## 🌐 Live Demo Access

| ▶️ Environment | 🔗 Access |
|---------------|----------|
| 🧠 **Open in Colab** | [Run directly in Google Colab (no setup required)](https://github.com/AaronKGoldman/IBM-Data-Analytics-Capstone/blob/main/1.%20Accessing%20APIs.ipynb) |
| 💻 **View on GitHub** | [Browse source code, data, and notebooks](https://github.com/Aarongoldmananalyst/IBM-Data-Analytics-Capstone) |
| 📄 **Executive Presentation (PDF)** | <a href="https://github.com/Aarongoldmananalyst/Winning-the-Space-Race-with-Data-Science/raw/main/Winning_the_Space_Race_with_Data_Science.pdf" target="_blank">Open executive slide deck</a> ||

---

## 🔌 API Data Collection

This project retrieves real-world data from external REST APIs and prepares it for downstream analysis.

**Key steps:**
- Connected to public REST APIs using Python (`requests`)
- Retrieved and parsed structured JSON responses
- Normalized API data into analysis-ready tables
- Validated and cleaned data prior to analysis and modeling

📓 **Notebook (API Integration):**  
- [1_Accessing_APIs.ipynb](https://github.com/AaronKGoldman/IBM-Data-Analytics-Capstone/blob/main/1.%20Accessing%20APIs.ipynb)

---

## 📘 About This Project

This repository is part of the **IBM Data Analytics Capstone**, demonstrating an end-to-end analytics workflow with a focus on **API-based data acquisition** and exploratory analysis.

The project highlights:
- Real-world data sourcing via external APIs  
- Practical data preparation for analytics use cases  
- Reproducible, notebook-driven analysis suitable for business and technical stakeholders  

🔗 **Primary Notebook:**  
- https://github.com/AaronKGoldman/IBM-Data-Analytics-Capstone/blob/main/1.%20Accessing%20APIs.ipynb

📓 **Notebook (API Integration):**  
- [1_Accessing_APIs.ipynb](https://github.com/AaronKGoldman/IBM-Data-Analytics-Capstone/blob/main/1.%20Accessing%20APIs.ipynb)

---

## 📘 About This Project

This repository is part of the **IBM Data Analytics Capstone**, demonstrating an end-to-end analytics workflow with a focus on **API-based data acquisition**, data preparation, and analytical exploration.

The project emphasizes:
- Real-world data sourcing via external APIs  
- Practical data engineering for analytics use cases  
- Reproducible, notebook-driven analysis suitable for business and technical stakeholders  

🔗 **Primary Notebook:**  
- https://github.com/AaronKGoldman/IBM-Data-Analytics-Capstone/blob/main/1.%20Accessing%20APIs.ipynb


## 📊 Analysis & Key Insights

This project focuses on analyzing historical data to identify trends, patterns,
and strategic insights related to technology skills demand and industry evolution.

Key outcomes include:
- Identification of high-growth programming languages and databases
- Trend analysis across time and regions
- Data-driven recommendations for workforce planning and skill development

---

## 🧭 About This Project

This project mirrors a **real-world analytics engagement**, complete with:
- **Data scraping** from SpaceX public sources  
- **SQL + Python integration** for analytics  
- **Predictive modeling** using scikit-learn  
- **Interactive visualizations** using Plotly and Folium 
- **Executive storytelling** deck for decision-making  

---

## 🧮 Data Overview

| Column | Description |
|:--------|:-------------|
| `launch_date` | Falcon 9 launch date |
| `launch_site` | Launch facility |
| `payload_mass_kg` | Payload mass in kilograms |
| `orbit` | Destination orbit (LEO, GEO, ISS, etc.) |
| `booster_version` | Falcon 9 booster version |
| `landing_outcome` | Landing result (Success/Failure) |
| `class` | Binary flag (1 = Success, 0 = Failure) |

> ⚙️ *Data sourced via web scraping (Wikipedia API) — all synthetic/public, no proprietary data.*

---

## 🧠 Machine Learning Performance

| Model | Accuracy | Notes |
|:--------|:----------|:----------|
| **Decision Tree** | 🟢 **86.7%** | Best overall performer |
| **SVM** | 83.3% | Strong linear classifier |
| **Logistic Regression** | 83.3% | Reliable baseline |
| **KNN** | 83.3% | Slower, less efficient |

🏁 **Winner:** Decision Tree — most accurate, interpretable, and deployment-ready.




---

## ⚙️ Tech Stack

| Layer | Tools |
|:-------|:------|
| **Languages** | Python, SQL |
| **Libraries** | Pandas, NumPy, scikit-learn, Seaborn, Plotly, Folium |
| **Visualization** | Plotly Dash, Matplotlib |
| **Database** | SQLite |
| **Environment** | Jupyter Notebook, Google Colab |
| **Version Control** | Git & GitHub |

---

## 🗂️ Repository Structure

├── README.md
├── requirements.txt
├── Space_Race_Analytics.ipynb
├── spacex_web_scraped.csv
├── visuals/
│   ├── space_race_banner.png
│   ├── launch_map.png 
├── docs/
    ├── Winning_the_Space_Race_with_Data_Science.pdf

---



## ⭐ Recruiter Highlights
- End-to-end analytics pipeline: raw data → ML models → executive insights
- Predictive modeling with 86.7% accuracy (Decision Tree)
- Strong SQL + Python integration for analytics workflows
- Executive storytelling focused on ROI and decision-making


---

## 💬 Lessons Learned

* Clean, verified data builds more trust than complex models.
* SQL + Python integration speeds up feature exploration.
* Visual analytics converts data into executive action.

---

##  👨‍🚀 Author

**Aaron Goldman**


Data Analyst | Machine Learning | Business Intelligence Storyteller

<p align="center"> <a href="https://linkedin.com/in/aaron-goldmans"><img src="https://img.shields.io/badge/Connect-LinkedIn-blue?logo=linkedin"></a> <a href="https://github.com/AaronKGoldman"><img src="https://img.shields.io/badge/View-GitHub-black?logo=github"></a> <a href="https://github.com/AaronKGoldman/Data-Science-Capstone-IBM"><img src="https://img.shields.io/badge/Open-Portfolio-orange?logo=python"></a> </p>

🚀 “Predicting rocket landings isn’t just about data science — it’s analytics with lift-off.”


🌌 Built for impact. Designed for recruiters. Ready for takeoff.

---

## 🧪 Quickstart

```bash
# 1️⃣ Clone the repo
git clone https://github.com/<YOUR-USERNAME>/Winning-the-Space-Race.git
cd Winning-the-Space-Race

# 2️⃣ Create environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the notebook
jupyter notebook Space_Race_Analytics.ipynb
