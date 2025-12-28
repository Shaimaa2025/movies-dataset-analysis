# 🎬 Movies Dataset Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-%234479A1.svg?style=for-the-badge&logo=python&logoColor=white)

---

## 📋 Project Overview

This project explores a dataset of 7,600+ movies to uncover the financial drivers of the film industry. By analyzing genres, budgets, and gross revenue, this study identifies what makes a movie commercially successful.

---

## 🧹 Advanced Data Engineering

To ensure high data quality, I implemented several sophisticated cleaning steps:

* **Dynamic Imputation:** Developed a strategy to fill missing numerical values using **Mean, Median, or Mode** based on the specific distribution shape of each feature.
* **Feature Engineering:** Extracted temporal data from release dates and addressed skewed data (Budget, Gross, Votes) using **Log Transformations** to normalize distributions for better correlation analysis.
* **Categorical Consistency:** Standardized genres and companies using Mode-based imputation.

---

## 📊 Key Insights & Visualizations

* **The Money Driver:** Found a strong positive correlation between **Budget** and **Gross Earnings**—investing more typically yields higher returns.
* **Profitability Growth:** Analysis shows the gap between budget and gross has widened over the decades, indicating industry-wide growth in profitability.
* **Genre Dominance:** Action, Comedy, and Animation lead the market in both investment and return.
* **Audience Engagement:** A clear link exists between the number of user **Votes** and total **Gross Earnings**.

---

## 🛠️ Tech Stack

* **Analysis:** Python (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn, Plotly Express (Interactive Maps)
* **Environment:** Jupyter Notebook / VS Code

---

**Author:** Dr. Shaimaa Gomaa  
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaimaa-gomaa-phd/)
