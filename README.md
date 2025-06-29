# 🎬 Movies Dataset Analysis

This project explores a dataset of movies to uncover insights related to **genre trends**, **budget**, and **gross revenue** over time. It demonstrates data cleaning, exploratory data analysis (EDA), and visualization using Python.

---

## 📁 Dataset

- **Source**: Local CSV file (`movies.csv`)
- **Columns**: title, genre, year, budget, gross
- **Size**: [The shape of the dataset is : (7668, 20)]

---


## 🧹 **Data Cleaning Process**
- 📅 Converted the `date` column to **datetime** format and extracted the date.
- 🛠 Applied a dynamic imputation strategy for **numerical columns**, choosing between **mean**, **median**, or **mode** based on distribution shape.
- 🧩 Filled missing values in **categorical columns** using the **mode** to maintain data consistency.
- 🚀 Addressed skewed features by applying **log transformations** to **budget**, **gross**, **votes**, and **runtime**.
- 🧮 **Note on log transformation:**  
  - While it improved the distribution, it also slightly reduced correlation values — a natural effect of compressing extreme values.

---

## 📊 Exploratory Data Analysis (EDA)

The notebook includes multiple insights and visualizations such as:

- 📈 Average gross revenue trends by genre (top 10 genres)
- 🎞️ Get top 10 campanies by number of movies
- 💸scatter plots to visulize the relationship between budget_log and other features 
- 📅 Line plot for budget and gross over the years
- Get  top 10  movies name, genre, star, and company by budget
- Movies by nationality map

Visualizations were created using:
- `Seaborn`
- `Matplotlib`
- `Plotly Express`

---


## 📊 **Key Results and Insights**
- 💰 A **strong positive correlation** was found between **budget** and **gross earnings**.
- 📈 The **gap between budget and gross** widened over the years, indicating increasing profitability.
- 🌟 Higher **votes** are associated with higher **gross earnings**.
- 🎬 **Top genres by budget and gross** are **Action**, **Comedy**, and **Animation**.
---

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Visual Studio Code

---

## 📁 Files Included
- `movie_dataset.ipynb`: Full analysis notebook
- `movies.csv`: Original dataset
- `images/`: Folder with exported visualizations
- `README.md`: Project documentation
#   m o v i e s - d a t a s e t - a n a l y s i s  
 