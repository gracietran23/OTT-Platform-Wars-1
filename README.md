# 🎬 Streaming Platforms Analysis: Market Trends & Strategic Positioning (1980 – 2026)

## 📌 Project Overview
This project delivers a comprehensive **Exploratory Data Analysis (EDA)** on the content catalogs of **10 major global streaming platforms** (Netflix, Amazon Prime Video, Disney+, Hulu, HBO Max, Apple TV+, Paramount+, Peacock, JioCinema, and Crunchyroll). 

By analyzing historical and current data up to 2026, the project identifies structural market trends, content quality distributions, and strategic positioning factors that drive each platform's unique competitive advantage.

* **Core Goal:** Analyze content scale, quality metrics,... to uncover the strategic strengths and content focus of each OTT provider.

* **Dataset:** 15,000+ titles with fields including IMDb/Rotten Tomatoes scores, budgets, awards, and watch-time data. [Source on Kaggle](http://kaggle.com/datasets/meruvakodandasuraj/streaming-content-catalog-netflix-prime-disney?select=streaming_catalog.csv)


## ⚙️ Analytical Workflow

### Phase 1: Data Preparation & Preprocessing
* **Data Overview:** Inspected data types, shapes, and structural integrity across the 15,000 records.
* **Missing Value Handling:** Systematically handled missing values in critical descriptive fields to prevent statistical bias.
* **Feature Engineering:** Segmented and engineered a custom "Content Quality Rating" based on weighted IMDb and Rotten Tomatoes scores to categorize titles into clear performance tiers.

### Phase 2: Exploratory Data Analysis (EDA)
* **Market Overview:** Mapped the macro-trends of content volume (Movies vs. TV Shows) and production growth rates from 1980 to 2026.
* **Performance Analysis:** Analyzed audience engagement trends over the last 5 years to evaluate active OTT strategies.
* **2026 Strategic Positioning:** Focused on the latest 2026 content drops and pinpoint where each platform is currently betting their resources.



## 💡 Key Insights Summary

| Analytical Factors | 🥇 Top 1 | 🥈 Top 2 |
| :--- | :--- | :--- |
| **📚 Content Library Scale** | Netflix | Amazon Prime Video |
| **🍅 Avg Rotten Tomatoes Score** | Apple TV+ | HBO Max |
| **⭐ Avg IMDb Rating** | Apple TV+ | HBO Max |
| **🏆 Total Awards Won** | Netflix | Amazon Prime Video |
| **🎬 Drama Performance (2026)** | HBO Max | Peacock |
| **🌍 The Final Matrix (2026)** | Apple TV+ | Amazon Prime Video | 




## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** `pandas` for data manipulation, `matplotlib` & `seaborn` for data visualization.
* **Design Theme:** Customized with a clean, cohesive visual palette tailored for streaming dashboard presentation to optimize readability.
