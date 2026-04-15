# 🍽️ Zomato Data Analysis Project

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on a Zomato restaurant dataset to uncover insights about customer preferences, pricing trends, and service features such as online ordering and table booking.

The analysis is done using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

---

## 📊 Objectives

* Analyze restaurant ratings and popularity
* Understand pricing distribution
* Evaluate impact of:

  * Online ordering
  * Table booking
* Compare performance across restaurant types

---

## 📁 Dataset Information

* Total Records: 148 restaurants
* Key Features:

  * `name` – Restaurant name
  * `online_order` – Availability of online ordering
  * `book_table` – Table booking availability
  * `rate` – Rating (out of 5)
  * `votes` – Number of votes
  * `approx_cost(for two people)` – Cost estimate
  * `listed_in(type)` – Restaurant category

---

## 🧹 Data Cleaning

* Converted ratings from string format (e.g., `4.1/5`) to numeric
* Handled missing/null values
* Standardized column formats

---

## 📈 Key Insights

### ⭐ Ratings

* Average rating: **3.63**
* Most restaurants fall between **3.3 – 4.0**

### 💰 Cost Analysis

* Average cost for two: **₹418**
* Majority are **mid-range restaurants**

### 📲 Online Ordering

* With online order: **Higher ratings (~3.86)**
* Without: **Lower ratings (~3.48)**

➡️ Online ordering improves customer satisfaction

### 🪑 Table Booking

* With booking: **~4.18 rating**
* Without: **~3.60 rating**

➡️ Premium restaurants offer table booking

### 🍽️ Category Analysis

* Buffet & Cafes have higher ratings than Dining

---

## 📊 Visualizations

The project includes:

* Rating distribution
* Cost vs Rating analysis
* Votes vs Rating
* Category-wise comparison

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone repository:

```bash
git clone https://github.com/your-username/zomato-data-analysis.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook:

```bash
jupyter notebook Zomato.ipynb
```

---

## 📌 Project Structure

```
zomato-data-analysis/
│
├── Zomato.ipynb        # Main analysis notebook
├── Zomato data.csv     # Dataset
├── README.md           # Project documentation
├── requirements.txt    # Dependencies
```

---

## 💡 Future Improvements

* Add Machine Learning model for rating prediction
* Build a Streamlit dashboard
* Deploy as a web app

---


## ⭐ If you like this project

Give it a ⭐ on GitHub!
