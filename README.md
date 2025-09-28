# 🎮 Safari City — Player Experience Analysis

## 📌 Project Overview
This project analyzes public player signals for **Safari City: Renovate & Design** by Maliyo Games.  
The goal is to demonstrate how data analytics can surface **player friction points** and inform **product improvements** that increase **retention, satisfaction, and monetization**.

I followed the **Google Data Analytics process (Ask → Prepare → Process → Analyze → Share)** and applied it to publicly available data sources.

---

## 🎯 Business Questions
- What themes appear in Safari City’s Play Store reviews?  
- How do ratings and sentiment change before and after the latest update (Sep 4, 2025)?  
- What actionable insights can we recommend to improve onboarding, gameplay balance, and overall player experience?  

---

## 📊 Dataset & Sources
- **Google Play Store metadata & reviews** for *Safari City: Renovate & Design*  
  - Installs: **100K+**  
  - Reviews analyzed: **61**  
  - Average rating: **4.3** (based on distribution below)  
- Public info from Maliyo Games & industry benchmarks for context  

---

## 🛠️ Tools & Methods
- **Python (pandas, matplotlib, seaborn, nltk/VADER)** → cleaning, visualization, sentiment analysis  
- **Google Play Scraper** → metadata & reviews  
- **Statistical Testing (Mann-Whitney U)** → comparing pre/post-update ratings  
- **Version control** → GitHub for reproducibility  

---

## 🔎 Key Findings
- **Ratings distribution:** Most reviews are 5-star (40/61), but there are clusters of **1-star reviews (8/61)** mentioning frustration.  
- **Sentiment analysis:**  
  - Positive = 47  
  - Neutral = 11  
  - Negative = 3  
  - → Reviews are **majority positive (77%)**, but negatives highlight onboarding difficulty and ads.  
- **Pre/Post Update:**  
  - Average rating before update = **3.93**  
  - After update = **4.53**  
  - Mann-Whitney test p = **0.36** → not statistically significant given small sample size, but **trend suggests improvements** after update.  

---

## ✅ Recommendations
1. **Onboarding** — further simplify early tutorial steps to reduce negative feedback.  
2. **Difficulty balancing** — monitor difficulty spikes around early levels; adjust curve.  
3. **Ads & monetization** — address ad-related complaints (frequency, reward reliability).  
4. **Data-driven validation** — run **A/B tests** on tutorial length & ad frequency once internal telemetry is available.  

---

## 📈 Visuals (generated in notebooks)
- Rating distribution histogram  
- Sentiment distribution pie chart  
- Time series chart of rolling average ratings  
- Word cloud of negative review keywords  

---

## 📂 Repo Structure
