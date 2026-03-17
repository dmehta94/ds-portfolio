# Data Science Portfolio — Deval Mehta

Recent graduate of the General Assembly Data Science Bootcamp (January 2025) with a BS in Mathematics and Physics (University of Delaware) and graduate coursework in computational physics and mathematics. My background is in quantitative reasoning and teaching, and my projects reflect an interest in civic data, social equity, and building tools that make analysis accessible. This repo collects my public data science work in one place.

---

## Projects

### [Connecting Queens: Transit Equity Analysis](https://github.com/dmehta94/project-capstone-transit-inequity-eastern-queens)
**Capstone | Python, MTA BusTime API, GeoPandas, HDBSCAN, Louvain community detection, SARIMA**

A transit equity analysis of 23 bus routes and 2,300 static stops across Eastern Queens, motivated by my experience growing up in the neighborhood. I collected one week of real-time bus position data via the MTA BusTime API, clustered stops into spatial communities using HDBSCAN, identified structurally underserved route communities via Louvain community detection on a weighted stop network, and validated daily service patterns using SARIMA forecasting. Of 27 identified communities, 17 qualify as low-service areas — confirming that Eastern Queens is severely underserved even relative to its own internal baseline.

---

### [AI Resume Optimizer](https://github.com/dmehta94/ai-resume-optimizer)
**Python, OpenAI GPT-4 API, pdfplumber, prompt engineering**

A command-line tool that automates resume analysis against job descriptions using GPT-4. Built during my job search to systematize ATS optimization across multiple applications. The tool extracts text from PDF resumes, sends structured prompts to GPT-4 requesting JSON output, and returns quantitative scores (ATS alignment 0-100%, Boolean match percentage), keyword gap analysis, and actionable recommendations. Reduces analysis time from ~2 hours to 5 minutes per job. Includes type hints throughout, Google-style docstrings, and robust error handling for production-quality code appropriate to entry-level data science portfolios.

---

### [NY State Renewable Energy Forecasting](https://github.com/dmehta94/project-5-new-york-state-of-energy)
**Group project | Python, scikit-learn, tslearn, Prophet, pandas, Matplotlib**

A group project advising the NY State Energy Planning Board on optimal regions for solar and wind infrastructure. As technical lead and project manager, I coordinated a team of five across ETL, clustering, forecasting, and cost analysis workstreams, independently researched and implemented the Time Series K-Means Clustering model (using soft-DTW metric via tslearn), and wrote the README. The model identified a clear upstate/downstate split in climatological zones, with the solar cluster concentrated in the NYC metro and lower Hudson Valley.

---

### [Reddit NLP: IP Litigation Classification](https://github.com/dmehta94/project-3-reddit-nlp-litigation-analysis)
**Python, PRAW, NLTK, scikit-learn, TF-IDF, VADER sentiment**

A binary text classifier that distinguishes posts from r/DungeonsAndDragons and r/Pathfinder_RPG, framed around a hypothetical Hasbro/Paizo IP dispute. I scraped nearly 4,000 posts using PRAW, built a custom POS-aware lemmatizer with VADER sentiment integration via a ColumnTransformer pipeline, and evaluated Logistic Regression, KNN, Random Forest, and SVC models across 3,254 TF-IDF features. Best test accuracy: 83.9% (Random Forest). All models overfit substantially, pointing to the need for stronger regularization, more aggressive feature reduction, and restricting the corpus to posts with body text.

---

### [Ames Housing Price Prediction](https://github.com/dmehta94/project-2-ames-housing-prediction)
**Python, scikit-learn, linear regression, feature engineering**

An iterative linear regression study on the Ames Housing Dataset, treating each preprocessing step — native numeric features, ordinal encoding, interaction terms, and scaling — as a controlled experiment with measured impact. Kaggle RMSE improved from $81,146 (baseline) to $32,484 across four submissions. The project documents exactly where OLS linear regression hits its ceiling and what would be needed next: log-transforming the target and Lasso regularization.

---

### [Education Outcomes and Wealth Inequality: A Global EDA](https://github.com/dmehta94/project-1-educational-outcomes-and-wealth-inequity)
**Python, pandas, Matplotlib, Seaborn | Gapminder, World Inequality Database**

An exploratory analysis asking whether educational attainment and wealth inequality co-vary meaningfully across a 14-country sample from 1998 to 2017. I cleaned and aligned six datasets, selected countries based on Gini index data completeness, and produced time-series visualizations for each variable. The central finding is null: education attainment rose consistently across the sample while inequality showed no coherent directional trend — a result that clarifies what data and methods would be needed to revisit the question.

---

## Contact

[GitHub @dmehta94](https://github.com/dmehta94) | [LinkedIn](https://www.linkedin.com/in/dmehta94/)