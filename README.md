# 🎮 Game Store: Predictive Analysis for Video Game Sales

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)

## 📌 Overview

This project analyzes global video game sales data to identify patterns that influence a game's commercial success. The analysis supports strategic decision‑making for marketing campaigns and product launches, with a specific focus on preparing insights for the year **2017**.

The project was developed as part of the **TripleTen Data Science Bootcamp** and demonstrates skills in data cleaning, exploratory data analysis (EDA), visualization, and statistical hypothesis testing.

---

## 📊 Business Questions

The analysis aims to answer key business questions, including:

* Which platforms are the most profitable, and which are declining?
* How do user and critic reviews impact global sales?
* Which genres generate the highest revenue globally and by region?
* How do regional preferences (NA, EU, JP) differ in platforms, genres, and ESRB ratings?
* Are there statistically significant differences between user ratings across platforms and genres?

---

## 🗂 Dataset

* **Source:** Video game sales dataset (`games.csv`)
* **Key Features:**

  * Sales by region (NA, EU, JP, Other)
  * Platform, genre, release year
  * Critic and user scores
  * ESRB ratings

---

## 🧹 Data Preparation

Key preprocessing steps include:

* Standardizing column names
* Handling missing values (`NaN`, `TBD`)
* Converting data types for analysis
* Creating a new feature: **total_sales** (global sales)

---

## 🔍 Analysis Performed

* Exploratory Data Analysis (EDA)
* Sales trends over time (2007–2015)
* Platform performance and lifecycle analysis
* Genre popularity and profitability
* Regional market segmentation (NA, EU, JP)
* Impact of critic vs. user reviews on sales
* ESRB rating influence on regional sales

---

## 📈 Statistical Tests

Hypothesis testing using **Student’s t‑test**, including:

* Comparison of user ratings between **Xbox One vs PC**
* Comparison of user ratings between **Action vs Sports** genres

Significance level: **α = 0.05**

---

## 🧠 Key Insights

* **PS4, Xbox One, and Xbox 360** dominate global sales.
* Critic scores show a **moderate positive correlation** with sales, while user scores show little correlation.
* Action and Sports genres generate the highest revenue globally.
* Strong regional differences exist:

  * **Japan:** RPGs, portable consoles, ESRB E ratings
  * **NA & EU:** Action, Sports, Shooter games dominate
* Statistically significant differences exist between Xbox One and PC user ratings.

---

## 🛠️ Tech Stack

* **Languages:** Python
* **Libraries:** Pandas, NumPy, SciPy, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, Git, GitHub

---

## 📁 Project Structure

```
game-store/
│
├── datasets/
│   └── games.csv
│
├── notebook/
│   └── notebook.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/PedroAlbuquerque25/game-store.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook

---

## 👤 Author

**Pedro Albuquerque**
Data Scientist | Business Intelligence

---

## 📌 Final Note

This project emphasizes **business‑oriented insights backed by statistical rigor**, demonstrating how data science can drive real strategic decisions in the gaming industry.

---

## 🤝 Contato
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/phaa/)
