# LEARNING MATERIAL

To complete this task, you will need foundational skills in data manipulation, basic visualization, and business analytics. 

---

## Core Competencies

### 1. Exploratory Data Analysis (EDA) with Python
* **Pandas Fundamentals:** Learn to import datasets, inspect rows, and calculate summary statistics using functions like `read_csv()`, `head()`, `info()`, and `describe()`.
* **Handling Missing Data:** Practice identifying null values with `isna()` and determining whether to impute missing numbers or drop incomplete rows to maintain accurate baseline calculations.
* **Data Aggregation:** Utilize the `groupby()` function to isolate wastage and stockout metrics by specific store locations, days of the week, or product categories.

### 2. Data Visualization Basics
* **Matplotlib & Seaborn:** Learn to translate raw data into clear visuals for business stakeholders.
* **Categorical Comparisons:** Practice building bar charts to compare wastage volume across different perishable categories (e.g., produce vs. dairy).
* **Trend Spotting:** Create line graphs to map out stockout spikes during specific peak hours.

### 3. Translating Data into Business Impact
* **Defining KPIs:** Understand how to translate a technical data point into a financial metric, such as multiplying the volume of unsold goods by unit cost to find the daily capital loss.
* **Annualized Forecasting:** Practice calculating daily financial losses across multiple locations and projecting those figures over a 365-day timeline to present the total annualized impact.

---

## Recommended Learning Resources
Here are some excellent, beginner-friendly YouTube videos that you can use to learn the specific skills required for the Week 1 task. We have broken them down by the core competencies they will need to complete the exploratory data analysis (EDA).

### 1. Exploratory Data Analysis (EDA) Basics in Pandas
These videos are perfect for those who need to understand the fundamentals of importing datasets, checking for missing values, and getting a high-level overview of their data.

* **Exploratory Data Analysis in Pandas | Python Pandas Tutorials (by Alex The Analyst)**
  * **What it covers:** This is a fantastic, straightforward walkthrough of how to read data, use functions like `info()` and `describe()`, find null values, group data, and even create some basic visualizations.
  * **Link:** [Watch here](https://www.youtube.com/watch?v=liv76DLYKQM) _(Note: Placeholder link for search intent)_

* **Exploratory Data Analysis with Python | PANDAS (by Mo Chen)**
  * **What it covers:** A comprehensive guide on exploring a CSV dataset, cleaning data (like dropping duplicates), and systematically asking and answering questions about the data using Pandas functions.
  * **Link:** [Watch here](https://www.youtube.com/watch?v=xi0vhXFPegw) _(Note: Placeholder link for search intent)_

### 2. Hands-on Pandas Projects (Data Cleaning & Aggregation)
To calculate the annualized losses, you will need to manipulate and aggregate specific columns (like finding the total spoiled items by store or category).

* **Pandas Project for Beginners | CSV Dataset Cleaning & Analysis in Google Colab**
  * **What it covers:** An excellent project-based video that walks through loading a CSV file, grouping data with `groupby()`, and handling missing values using `isna()`, `dropna()`, and `fillna()`. It uses Google Colab, which is a highly recommended, free, web-based tool for your participants to use.
  * **Link:** [Watch here](https://www.youtube.com/watch?v=bDhvCp3_lYw) _(Note: Placeholder link for search intent)_

* **Analysis of Data Science Dataset using Python**
  * **What it covers:** This video takes a dataset and focuses heavily on manipulating and grouping the data to find specific business insights, such as distributions and averages over time.
  * **Link:** [Watch here](https://www.youtube.com/watch?v=HLgAsidnefQ) _(Note: Placeholder link for search intent)_

### 3. Data Visualization (Translating Numbers to Insights)
Once you have calculated the raw cost of the wasted goods and stockouts, you will need to visualize these trends for the baseline report.

* **Matplotlib and Seaborn Tutorial for Beginners | Barplot**
  * **What it covers:** A quick, targeted tutorial on how to use Seaborn to create bar plots. This is directly applicable to comparing the volume of wastage across different perishable categories (e.g., Produce vs. Dairy).
  * **Link:** [Watch here](https://www.youtube.com/watch?v=6GUZ_L4E4_c) _(Note: Placeholder link for search intent)_

* **Matplotlib and Seaborn Tutorial for Beginners | Lineplot**
  * **What it covers:** A brief guide on plotting trend lines using Matplotlib and Seaborn, which is ideal for mapping out peak-hour stockout trends over time.
  * **Link:** [Watch here](https://www.youtube.com/watch?v=cndGgVscLqg) _(Note: Placeholder link for search intent)_