# Exploring World Cup Data

### 📖 About the Project  
This case study explores **over 44,000 international football matches** from **1872 to 2022**, including tournaments such as the FIFA World Cup and other international fixtures. Using **Python** and **pandas**, the project demonstrates core **Exploratory Data Analysis (EDA)** and **data manipulation** techniques.

> 📊 Data Source: [International Football Results (GitHub - martj42)](https://github.com/martj42/international_results)

---

### ⚽ Dataset Overview  
The dataset includes the results of men’s full international matches — excluding Olympic Games and matches involving B-teams, U-23, or league select teams.  
Each record contains:
- Date and year of the match  
- Home and away teams  
- Match scores  
- Tournament name  
- Match location  

Total records: **44,066 matches (1872–2022)**

---

### 🧠 Learning Goals
- Perform **data import, cleaning, and transformation** with `pandas`
- Explore **FIFA World Cup data** within the broader dataset
- Visualize data using **Plotly Express**
- Understand **patterns in goals, tournaments, and match frequency**

---

### 🧩 Project Tasks Overview

#### **Task 1: Import and Prepare the Dataset**
- Load `results.csv` using pandas  
- Convert date column to datetime and extract the year  

#### **Task 2: Filter for FIFA World Cup Matches**
- Count matches per tournament  
- Filter only `"FIFA World Cup"` entries  

#### **Task 3: Number of Matches per World Cup**
- Count matches by year  
- Visualize with a **Plotly bar chart**

#### **Task 4: Highest Goal Difference**
- Add a `goal_difference` column  
- Query for the match with the largest goal gap  

#### **Task 5: Highest Total Goals**
- Add a `total_goals` column  
- Query for the match with the most combined goals  

#### **Task 6: Top Scoring Countries**
- Aggregate home and away goals by team  
- Combine totals and visualize via a **Plotly choropleth map**

---

### 🧮 Tools & Libraries Used
- **Python 3**
- **pandas** — data loading and manipulation  
- **plotly.express** — data visualization  
- **numpy** — numerical operations (optional use)

---

