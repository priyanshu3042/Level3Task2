# 🍽️ Customer Preference Analysis – Zomato Dataset

**Level 3 - Task 2 | Cognifyz Technologies Internship**

This project analyzes customer preferences from a restaurant dataset, focusing on the relationship between cuisine types, customer ratings, and popularity based on votes. The goal is to identify trends and insights that can help restaurants better understand which cuisines are most favored by customers.

---

## 🧠 Objective

- 📊 **Analyze** the relationship between different types of cuisines and restaurant ratings.
- 🥇 **Identify** the most popular cuisines based on total customer votes.
- ⭐ **Determine** which cuisines tend to receive higher ratings consistently.

---

## 🗂️ Dataset

The dataset used for this analysis is named **`Dataset .csv`** (from the Zomato dataset), containing fields like:

- `Cuisines` – Type(s) of cuisine offered
- `Aggregate rating` – Average user rating
- `Votes` – Number of votes given by customers

---

## 🧪 Technologies Used

- **Python**
- **Pandas** – Data cleaning and manipulation
- **Matplotlib & Seaborn** – Visualizations
- **Jupyter/Colab Notebook**

---

## 📈 Analysis Workflow

1. **Data Cleaning**:
   - Removed missing values and rows with zero votes
   - Handled multiple cuisines in one cell using `.explode()`

2. **Feature Engineering**:
   - Separated individual cuisines from multi-cuisine entries
   - Aggregated by cuisine to calculate total votes and average rating

3. **Visualization**:
   - Bar charts for top cuisines by votes and rating
   - Scatter plot showing relation between total votes and rating

---

## 📊 Sample Insights

- **Most Popular Cuisines** (by votes) are typically broad-appeal options like *North Indian*, *Chinese*, etc.
- Some niche cuisines might have **higher average ratings** even with fewer votes.
- There is not always a direct relationship between popularity (votes) and rating.

---

## 📸 Visual Outputs

- Bar plot of top 10 cuisines with highest total votes
- Bar plot of top 10 cuisines with highest average ratings
- Scatter plot: Votes vs Ratings across all cuisines

---


