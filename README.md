#  Evolution of NBA Playing Styles: An Advanced Statistical Analysis

## Overview
This project analyzes how **NBA playing styles** have evolved over time using the **NBA–ABA–BAA player statistics dataset** from [Kaggle](https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats).  
We focus on the **Advanced Statistics** file (`player_stats_advanced.csv`) and apply data science techniques to answer research questions that matter for both fans and professionals.

---

## Research Questions
1. **Era Comparison: Who Would Dominate?**  
   - Compare player statistics across decades, adjusting for pace and league averages.  
   - Use z-scores, effect sizes (Cohen’s *d*), and distributional tests (KS test, Mann–Whitney).  

2. **Positionless Basketball: Do Bigs Look Like Guards?**  
   - Analyze whether modern PF/Cs statistically resemble guards in shot selection and playmaking.  
   - Apply PCA for dimensionality reduction and K-Means clustering to study convergence.  

3. **Career Longevity Prediction: Who Lasts 10+ Years?**  
   - Build models (Logistic Regression, Random Forest) to predict whether a player will have a 10+ year career.  
   - Features include early-career efficiency, usage, and physical attributes.  

4. **Cross-Era Archetypes: How Do Player Roles Shift?**  
   - Cluster players into archetypes (e.g., Rim Protector, Stretch Big, 3&D Wing).  
   - Track cluster prevalence and centroid drift over decades.

---

## Dataset
- **File used:** `player_stats_advanced.csv`  
- **Unit of analysis:** Player–season record  
- **Key features:**  
  - Efficiency metrics: `TS%`, `PER`, `WS`, `BPM`, `VORP`  
  - Style metrics: `3PAr`, `FTr`, `USG%`  
  - Role metrics: `AST%`, `TRB%`, `STL%`, `BLK%`  
- **Coverage:** From BAA (1946–49), ABA (1967–76), to modern NBA seasons.

---

## Methods & Tools
- **Python libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, SciPy  
- **Data preprocessing:** Standardization, pace adjustment, z-scores  
- **Statistical tests:** KS test, Welch’s *t*, Mann–Whitney *U*, Cohen’s *d*  
- **Machine Learning:** Logistic Regression, Random Forest, PCA, K-Means  

---

## Exploratory Data Analysis (EDA)
- **Missingness:** Early seasons lack 3-point statistics before 1979–80.  
- **Trends:**  
  - 3PAr shows exponential growth since the 1980s.  
  - TS% has steadily improved (efficiency gains).  
  - FTr and USG% show role- and era-dependent variation.  

---

## Project Structure
