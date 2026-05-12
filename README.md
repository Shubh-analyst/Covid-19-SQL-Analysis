# 🦠 Covid-19 Data Analysis

A complete end-to-end SQL data analysis project 
exploring global Covid-19 trends across 81,000+ rows 
of real-world data using PostgreSQL and pgAdmin.

---

## 🛠️ Technologies

- PostgreSQL
- pgAdmin 4
- SQL
- Microsoft Excel
- Dataset: Our World in Data

---

## 📊 Features

Here's what this project analyzes:

- **Death Percentage**: If you contracted Covid in a 
specific country, what was your chance of dying?

- **Population Infected**: What percentage of each 
country's population got infected?

- **Highest Infection Count**: Which countries had 
the most cases relative to population?

- **Total Death Count**: Which countries and 
continents had the highest death toll?

- **Global Death Percentage**: How did the worldwide 
death rate change over time?

- **Vaccination Rollout**: How did new vaccinations 
roll out across countries over time?

---

## 🔑 Key Insights

- 🌍 Total worldwide cases: **151 Million+**
- 💀 Total worldwide deaths: **3.18 Million**
- 📉 Global death rate: **~2.1%**

**Deaths by Continent:**
| Continent | Total Deaths |
|---|---|
| Europe | 1,016,750 |
| North America | 847,942 |
| South America | 672,415 |
| Asia | 520,286 |
| Africa | 121,784 |
| Oceania | 1,046 |

---

## 📸 Screenshots

### 1️⃣ Percentage of Population Infected


![Population Infected](screenshot1.png)



### 2️⃣ Highest Infection Count by Country


![Highest Infection Count](screenshot2.png)



### 3️⃣ Death Percentage Across Globe


![Death Percentage Globe](screenshot3.png)



### 4️⃣ Death Percentage by Country


![Death Percentage Country](screenshot4.png)



### 5️⃣ Vaccination Rollout JOIN Query


![Vaccination JOIN](screenshot5.png)



### 6️⃣ Highest Infection Count Mobile View


![Mobile View](screenshot6.png)



---

## ⚙️ The Process

I started by setting up PostgreSQL and importing the 
Covid-19 CSV dataset into pgAdmin.

The data had multiple type mismatches and null values 
which required careful casting and cleaning before 
any analysis could begin.

I then wrote 7 SQL queries progressively — starting 
from simple SELECT statements to complex JOINs across 
two tables.

Each query was designed to answer a specific business 
question rather than just retrieve data.

Along the way I debugged 6+ errors including 
permission denied issues, numeric overflow errors, 
and missing column mismatches.

This taught me that real-world data is never clean — 
and that debugging IS the skill.

---

## 🧠 What I Learned

### 🔴 Data Type Handling
- **Type Casting**: Used CAST(column AS NUMERIC) to 
handle mixed data types in real datasets
- **NULL Management**: Used NULLIF() to avoid 
division by zero errors

### 🔗 JOIN Operations
- **Multi-table Analysis**: Joined Covid Deaths and 
Vaccinations tables on location and date
- **Real World JOINs**: Multiple conditions give 
more accurate results

### 📊 Aggregate Functions
- **GROUP BY mastery**: Used SUM, MAX, COUNT across 
multiple dimensions
- **Business thinking**: Aggregates change meaning 
depending on GROUP BY columns

### 🛠️ Database Setup
- **Full workflow**: From creating database to 
importing CSV to querying
- **Permission handling**: Solved real server 
permission errors during CSV import

### 💡 Business Thinking
- **Data storytelling**: Connected query results to 
real business decisions
- **Insight extraction**: Every query built around 
a real-world question

---

## 🔧 How Can It Be Improved?

- Add Python Pandas analysis on same dataset
- Build Power BI dashboard for visualization
- Add time series analysis of vaccination impact
- Include rolling averages for smoother trends
- Add country-wise GDP vs death rate correlation

---

## 🚀 Running the Project

1. Install PostgreSQL and pgAdmin 4
2. Create a new database called PortfolioProject
3. Run CREATE TABLE scripts from queries.sql
4. Import CovidVaccinations.csv and CovidDeaths.csv
5. Run queries one by one from queries.sql
6. View results in Data Output tab

---

## 👨‍💻 About Me

First-year B.Tech Information Technology student at 
Bharati Vidyapeeth College of Engineering, Pune.
Building my Data Analytics portfolio from Day 1.

🔗 LinkedIn: linkedin.com/in/shubh-chaturvedi-48b02537a
