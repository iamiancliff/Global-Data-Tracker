# 🌍 COVID-19 Global Data Tracker

## 📌 Project Description

Welcome to my **COVID-19 Global Data Tracker** project. This is a data analysis project I built using Python and Jupyter Notebook to explore how COVID-19 has impacted different countries over time. Using real-world data from *Our World in Data*, I cleaned, processed, and visualized key metrics like total cases, deaths, and vaccinations. The aim was to uncover trends, compare countries, and tell a clear story through data.

This project not only helped me strengthen my data analysis and visualization skills but also deepened my understanding of global pandemic trends. Whether you're a fellow learner, data enthusiast, or just curious, feel free to explore the notebook, visuals, and insights — I hope you enjoy going through it as much as I enjoyed creating it!

---

## 🚩 Project Objectives

- ✅ Import and clean COVID-19 global data  
- ✅ Analyze time trends (cases, deaths, vaccinations)  
- ✅ Compare key metrics across countries  
- ✅ Visualize trends using charts and maps  
- ✅ Communicate findings through visuals and narrative insights  

---

## 🗂️ Project Structure (Step-by-Step)

### 1️⃣ Data Collection

**Goal:** Get reliable COVID-19 data.

- **Source Used:** [Our World in Data - COVID-19 Dataset](https://www.kaggle.com/datasets)
- A cleaned CSV file (`owid-covid-data.csv`) was used for ease of analysis.

---

### 2️⃣ Data Loading & Exploration

**Goal:** Load the dataset and understand its structure.

**Tasks:**
- Load data using `pandas.read_csv()`
- View column names and sample rows
- Check for missing values

**Key Columns Used:**  
`date`, `location`, `total_cases`, `total_deaths`, `new_cases`, `new_deaths`, `total_vaccinations`, etc.

---

### 3️⃣ Data Cleaning

**Goal:** Prepare the dataset for analysis.

**Tasks:**
- Filter countries of interest (e.g., Kenya, USA, India)
- Convert `date` column to datetime
- Remove or fill missing values
- Handle inconsistencies

---

### 4️⃣ Exploratory Data Analysis (EDA)

**Goal:** Explore patterns in cases and deaths.

**Tasks:**
- Plot total cases and deaths over time
- Compare daily new cases between countries
- Calculate death rates (`total_deaths / total_cases`)

**Tools:** `matplotlib`, `seaborn`

---

### 5️⃣ Vaccination Analysis

**Goal:** Understand vaccine rollout progress.

**Tasks:**
- Plot cumulative vaccinations over time
- Compare vaccination percentages among countries

**Charts Used:** Line charts 

---

### 6️⃣ Insights & Reporting

**Goal:** Share key takeaways.

**Tasks:**
- Summarize findings with 3–5 key insights
- Highlight trends, anomalies, and comparisons
- Use Markdown in the notebook for clear reporting

---

## 📊 Tools & Technologies

- 🐍 Python  
- 📓 Jupyter Notebook  
- 🧮 pandas  
- 📈 matplotlib


---

## 💡 Key Insights

- The United States consistently recorded the highest total number of COVID-19 cases throughout the pandemic.
- India saw a massive spike in cases during mid-2021, coinciding with the Delta variant wave.
- Kenya’s cases remained relatively lower compared to other selected countries but saw several surges.
- Vaccination efforts ramped up in 2021, with some countries reaching over 60% of their population vaccinated quickly.
- There is a strong positive correlation between total cases and total deaths, but the death rate (% of deaths out of cases) varies across countries.

---

## 🧠 What I Learned

- How to handle and clean large real-world datasets  
- How to perform exploratory data analysis (EDA) using Python  
- How to build and interpret line and bar charts  
- How to draw insights and communicate them clearly with visuals  

---

## 🙌 Acknowledgements

- [Our World in Data](https://www.kaggle.com/datasets) for the dataset  
- Open-source Python libraries 
