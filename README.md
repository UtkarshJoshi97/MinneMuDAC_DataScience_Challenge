# MinneMuDAC_DataScience_Challenge
Link: https://minneanalytics.org/minnemudac-2025/

Code on Colab: https://colab.research.google.com/drive/1zlA1NOLBQXLGZvM_gifJzRj5mvxvrDV8#scrollTo=p5CrRgeqbI-5 (Individual Contribution).

# 🤝 MinneMUDAC 2025 Challenge – Big Brothers Big Sisters Twin Cities

## Overview

This project is developed as part of the **MinneMUDAC 2025 Data Science Challenge**, in collaboration with **Big Brothers Big Sisters Twin Cities (BBBSTC)** — a leading youth mentorship organization supporting matches between adult volunteers (Bigs) and children (Littles). 

The central goal is to understand and predict the **Match Length** and **Closure Reason** of mentorship pairings using demographic data, match dynamics, and unstructured support call notes. By building robust analytical and predictive models, this project aims to help BBBSTC **identify at-risk matches**, **understand factors driving successful outcomes**, and **design early intervention strategies**.

---

## Data Sources

Different datasets were provided based on division levels:

- `Novice.xlsx` – for foundational analysis
- `Training.xlsx` and `Test-Truncated.xlsx` – for predictive modeling
- Open text fields: **Match Support Contact Notes**, **Rationale for Match**, **Closure Details**
- Geographic metadata: **Census Block Group ID**

---

##  Novice Division

### Objectives:
- Analyze distribution of:
  - **Match Length**
  - **Closure Reason**
- Compare distributions across:
  - **Program Type**
  - **Time Periods**
  - **Big/Little demographics**
  - **Demographic and interest alignment** (e.g. same gender, shared hobbies)

### Success Criteria:
- A match is considered successful if it:
  1. Remains active
  2. Lasts a long time
  3. Ends due to age of Little
  4. Closes with “Successful Match Closure”

### Deliverables:
- Statistical insights into factors driving successful or unsuccessful matches
- Visualization of how match outcomes vary over time and by demographic alignment

---

## Undergraduate Division

### Additional Objectives:
- Explore how **cadence of Match Support Calls** impacts Match Length
- Conduct **text mining** on **Match Support Contact Notes**:
  - Identify relevant keywords, phrases, and sentiment
  - Examine changes over different match stages (early vs late)
- Design a **questionnaire for Match Support Coordinators**:
  - Drop-down structured questions to assess risk of closure within 3–6 months
  - Informed by both structured data and insights from unstructured text

### 🤖 Predictive Modeling:
- Build a **regression model to predict Match Length**
- Train on `Training.xlsx`, predict on `Test-Truncated.xlsx`
- Evaluation metric: **Root Mean Squared Error (RMSE)**

---

##  Graduate Division

### Advanced Analytical Goals:
- Perform **text analysis on multiple open fields**:
  - Match Support Contact Notes
  - Rationale for Match
  - Closure Details
- Analyze **emotional tones** in support calls
- Identify features influencing both **Match Length** and **Closure Reason**
- Generate deeper insights using **natural language processing (NLP)**

### Intervention Strategy:
- Propose strategies to **reduce early closures**
- Build an **early risk detection model** using structured and unstructured data
- Determine **most important predictive factors** for early intervention

### Census Data Enrichment:
- Integrate **Census Block Group data** to:
  - Understand socio-economic or geographic trends in match outcomes
  - Provide location-aware insights for better program targeting

---

## Project Outcomes

By the end of this project, the deliverables will include:

- Exploratory and statistical analysis of match dynamics
- Predictive modeling for Match Length (with tested generalization)
- Text mining and sentiment analysis of support notes
- A structured risk-assessment questionnaire for coordinators
- Policy recommendations and intervention strategies for BBBSTC
- Geographic enrichment with publicly available Census data

---

##

