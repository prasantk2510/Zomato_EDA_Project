# 🍽️ Zomato Restaurant Data - Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-9cf)

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on a Zomato restaurant dataset to uncover insights about customer ordering behavior, restaurant ratings, spending patterns, and more.
---

## 📁 Project Structure

```
Zomato-EDA-Project/
│
├── Zomato_project.ipynb   # Main Jupyter Notebook with full analysis
├── Zomato_data.csv        # Dataset containing restaurant information
└── README.md              # Project documentation
```
---

## 📁 Files

| File | Description |
|------|-------------|
| `Zomato_project.ipynb` | Main Jupyter Notebook with full analysis |
| `Zomato_data_.csv` | Dataset containing restaurant information |

---

## 📊 Dataset Features

| Column | Description |
|--------|-------------|
| `name` | Name of the restaurant |
| `online_order` | Whether online ordering is available (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Customer rating of the restaurant |
| `votes` | Total number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people |
| `listed_in(type)` | Category/type of the restaurant |

---

## ❓ Key Questions Answered

1. **Q1** — What type of restaurant do the majority of customers order from?
2. **Q2** — How many votes has each type of restaurant received from customers?
3. **Q3** — What are the ratings that the majority of restaurants have received?
4. **Q4** — What is the average spending of couples per online order?
5. **Q5** — Which order mode (online or offline) has received the highest rating?
6. **Q6** — Which types of restaurants receive more offline orders?

---

## 🔍 Key Findings

- **Dining** restaurants are the most popular category among customers.
- **Dining** restaurants have received the maximum number of votes.
- Most restaurants have a rating between **3.5 and 4.5**.
- The most frequent spending amount for couples is **₹300**.
- **Online** ordering mode has received the highest average rating.
- **Dining** restaurants receive the highest number of offline orders.

---

## 🛠️ Libraries Used

- `NumPy` — Numerical computations
- `Pandas` — Data manipulation and analysis
- `Seaborn` — Data visualization
- `Matplotlib` — Plotting charts

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Zomato-EDA-Project.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Zomato-EDA-Project
   ```
3. Install the required libraries:
   ```bash
   pip install numpy pandas seaborn matplotlib
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Zomato_project.ipynb
   ```

---

## 👤 Author

**prasant kumar **  
[GitHub](https://github.com/your-username) | [LinkedIn](www.linkedin.com/in/prasant-kumar-137750359)
