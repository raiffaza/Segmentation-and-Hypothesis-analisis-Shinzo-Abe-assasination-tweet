---

# 📊 Shinzo Abe Sentiment & Engagement Analysis

## 📌 Overview

This project analyzes Twitter reactions to the assassination of Shinzo Abe.
The objective is to examine whether sentiment polarity (positive vs. negative) influences engagement behavior during high-impact political events.

The analysis combines sentiment scoring, engagement segmentation, and statistical hypothesis testing to uncover structural differences in online discourse.

---

## 🧠 Research Questions

1. Do positive and negative tweets differ in average virality?
2. Does engagement distribution differ across sentiment categories?
3. Is public reaction driven more by praise or by crisis-oriented framing?

---

## 🔧 Methodology

### 1️⃣ Data Preparation

* Data cleaning and duplicate removal
* Date parsing and normalization
* Country normalization (where applicable)
* Filtering for organic tweets

### 2️⃣ Sentiment Analysis

* Sentiment scoring using **VADER**
* Labeling tweets into:

  * Positive Statement
  * Neutral Statement
  * Negative Statement

### 3️⃣ Engagement Segmentation

* Aggregation of retweet counts
* Mean vs. Median comparison
* Distribution inspection (skewness & outlier analysis)

### 4️⃣ Hypothesis Testing

Two statistical tests were conducted:

* **Independent T-Test** → Compare mean engagement
* **Mann–Whitney U Test** → Compare engagement distributions

Additional validation:

* Probability of receiving engagement (>0 retweets)

---

## 📊 Key Findings

* No statistically significant difference in average retweet counts between positive and negative tweets.
* A significant difference in engagement distribution was detected.
* Negative tweets are more consistently likely to receive interaction.
* Crisis discourse appears to be reaction-driven rather than praise-driven.

---

## 🔎 Core Insight

While large viral spikes occur across sentiments, consistent engagement during crisis events is more strongly associated with negative framing.

---

## 📁 Project Structure

```
├── shinzoabe.ipynb              # Main analysis notebook
├── ShinzoabeCombinedTweets.csv           # Raw Twitter dataset (if included)
├── shinzo abe analysis, final.pdf            # Presentation slides (optional)
```

---

## 📌 Tools & Libraries

* Python
* pandas
* NumPy
* matplotlib
* VADER Sentiment Analysis
* SciPy (Statistical Testing)

---

## 🚀 Author

Naufal Dzakia Raiffaza
Data Analyst | Data Scientis

---
