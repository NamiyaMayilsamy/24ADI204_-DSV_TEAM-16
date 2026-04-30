# Flight Delay Analysis and Prediction Engine

A data science project analyzing 2017 U.S. domestic flight data to understand patterns in flight delays and build a foundation for delay prediction.

**Team:** DSV_TEAM_16  
**Dataset:** 2017 U.S. Domestic Flights (~5 million rows, sampled to 200,000 for analysis)

---

## What this project does

This project takes raw flight data and works through it in stages — cleaning it, exploring patterns, engineering features for modelling, and visualizing findings in a Power BI dashboard.

---
## Why this matters

Flight delays cost airlines, airports, and passengers significant time and money every year.
This project helps answer practical questions like:

- Which airlines and airports are most delay-prone?
- What time of year should you avoid flying if you want to be on time?
- If a flight departs late, how likely is it to arrive late?
- Can we use flight details (distance, taxi time, departure delay) to predict whether a flight will be delayed?

The analysis can be useful for:

- **Passengers** — making smarter booking decisions based on historical delay patterns
- **Airlines** — identifying operational bottlenecks at specific airports or routes
- **Airport management** — understanding peak delay periods to better allocate resources
- **Researchers / students** — as a reference for end-to-end data science workflow on real-world data

## Key findings

- Around 40% of U.S. domestic flights in 2017 experienced some arrival delay
- Departure delay and arrival delay have a very high correlation (~0.9) — a late departure almost always means a late arrival
- Summer (June–July) and December show the highest average delays due to weather and travel volume
- Delay data is heavily right-skewed; log transformation was applied to normalize it for modelling

---

## Tech stack

- **Python** (Google Colab) — data cleaning, EDA, feature engineering, PCA
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Visualization:** Power BI (dashboard), Matplotlib/Seaborn (notebook plots)

---

## How to run

1. Open the notebook in Google Colab
2. Upload `2017_dataset.csv` when prompted
3. Run cells sequentially — each week builds on the previous one
4. The cleaned dataset (`final_cleaned_dataset.csv`) is saved automatically after Week 3
