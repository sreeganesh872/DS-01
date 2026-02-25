

# DS-01 — Student Performance Analysis

## Overview

This project analyzes the Students Performance dataset using a structured data workflow:

* Data ingestion
* Preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Interpretation

All analysis was performed using Python (pandas, matplotlib).

---

## Dataset

The dataset includes:

* Gender
* Lunch type
* Test preparation course
* Math, Reading, Writing scores

An additional feature `overall_avg` was created as the average of the three subjects.

---

## Visualizations

1. **Gender vs Math & Reading**
   Reading shows clearer gender differences than math.

2. **Test Preparation vs Math**
   Students who completed test prep generally scored higher in math.

3. **Lunch Type vs Overall Average**
   Standard lunch students performed better overall.

4. **Subject Correlation Heatmap**
   Math, reading, and writing are strongly positively correlated.

5. **Math vs Reading (by Test Prep)**
   Strong positive relationship; test prep shifts performance upward.

---

## Tech Stack

* Python
* pandas
* matplotlib
* numpy
* scipy

---

## Repository Structure

```
DS-01/
│
├── data/
├── figures/
├── reports/
└── README.md
```

---
