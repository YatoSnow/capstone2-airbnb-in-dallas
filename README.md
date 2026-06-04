# Airbnb Dallas — Guest Satisfaction NLP Analysis

Unsupervised NLP analysis of 219K+ Airbnb guest reviews for Dallas listings to identify key drivers of guest satisfaction.

---

## Project Overview

This project applies natural language processing techniques to a large corpus of Airbnb guest reviews from Dallas, TX. By uncovering latent topics in unstructured review text, the analysis provides actionable insights into what guests value most — and where hosts can improve — without relying on explicit ratings alone.

---

## Goals

- Identify topic clusters in guest reviews using unsupervised NLP
- Analyze sentiment patterns across listing types and neighborhoods
- Support data-driven host strategy recommendations for improving guest experience
- Build a regression-based model to explore the relationship between review themes and revenue performance

---

## Methods

| Step | Technique |
|------|-----------|
| Text preprocessing | Tokenization, stop-word removal, lemmatization |
| Topic modeling | Non-negative Matrix Factorization (NMF) and Latent Dirichlet Allocation (LDA) |
| Exploratory data analysis | Distribution analysis, geo-visualization by neighborhood |
| Revenue modeling | Regression-based optimization with feature engineering |

---

## Tools & Libraries

- **Language:** Python 3
- **Data manipulation:** pandas, NumPy
- **NLP & modeling:** scikit-learn
- **Visualization:** Matplotlib, seaborn
- **Environment:** Jupyter Notebook

---

## Dataset

Data sourced from [Inside Airbnb](http://insideairbnb.com/) — Dallas, TX snapshot.

| File | Description |
|------|-------------|
| `listings.csv` | Listing metadata: price, room type, neighborhood, host info |
| `neighbourhoods.geojson` | GeoJSON boundaries for Dallas neighborhoods |

> Review text data was processed directly within the notebooks from the Inside Airbnb reviews export.

---

## Repository Structure

```
capstone2-airbnb-in-dallas/
├── Dallas_AIRBNB.ipynb                  # Exploratory data analysis: distributions, geo-mapping, review volume
├── 11.5 Dallas_AIRBNB.ipynb             # Iterative EDA notebook with additional feature exploration
├── modelling Dallas_AIRBNB.ipynb        # NLP topic modeling (NMF & LDA) and regression modeling
├── Capstone Two_ Project Proposal.pdf   # Original project proposal outlining objectives and methodology
├── listings.csv                         # Airbnb listings data for Dallas
└── neighbourhoods.geojson               # Neighborhood boundary data for spatial analysis
```

---

## Key Findings

- NMF and LDA both surfaced consistent topic clusters around **cleanliness**, **location convenience**, **host responsiveness**, and **value for price**
- Neighborhood context plays a significant role in guest sentiment, with listings near downtown and entertainment districts receiving distinct feedback patterns
- Review-derived features show meaningful correlation with pricing and occupancy proxies, supporting their use in host strategy models

---

## Author

**Esref Selvi**

[![GitHub](https://img.shields.io/badge/GitHub-YatoSnow-181717?style=flat&logo=github)](https://github.com/YatoSnow)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-esrefselvi-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/esrefselvi)

---

*Completed as Capstone Project 2 for the Springboard Data Science Fellowship.*
