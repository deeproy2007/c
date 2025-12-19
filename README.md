# Netflix Movies & TV Shows Data Analysis

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset to understand content trends, popular categories, top countries, directors, and movie duration patterns. The analysis focuses on **data cleaning, statistical exploration, and visualization** using Python.

---

## Dataset Details
- **Dataset Name:** netflix_titles.csv  
- **Description:**  
  The dataset contains information about Netflix content, including:
  - Title  
  - Type (Movie / TV Show)  
  - Director  
  - Cast  
  - Country  
  - Date Added  
  - Rating  
  - Duration  
  - Listed Categories (Genres)  

---

## Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- NumPy  

---

## Analysis Steps

### 1. Data Loading
- Imported required Python libraries.
- Loaded the dataset using Pandas.
- Displayed initial records to understand the data structure.

**Goal:** Understand dataset layout and available columns.

---

### 2. Missing Value Treatment
- Checked missing values across all columns.
- Removed rows with null values in important fields:
  - Director  
  - Cast  
  - Country  
  - Date Added  
  - Rating  
  - Duration  

**Goal:** Improve data quality and ensure accurate analysis.

---

### 3. Movies vs TV Shows Distribution
- Analyzed the `type` column.
- Visualized the count of Movies and TV Shows using a bar chart.

**Goal:** Identify which content type dominates Netflix.

---

### 4. Top 10 Content Categories
- Analyzed the `listed_in` column.
- Extracted and visualized the top 10 most common categories.

**Goal:** Understand popular genres on Netflix.

---

### 5. Top 10 Content Producing Countries
- Counted titles by country.
- Sorted and visualized the top 10 countries.

**Goal:** Identify countries contributing the most content.

---

### 6. Top 10 Directors
- Analyzed the `director` column.
- Identified directors with the highest number of titles.
- Visualized the top 10 directors.

**Goal:** Highlight key contributors to Netflix content.

---

### 7. Movie Duration Analysis
- Filtered only Movies from the dataset.
- Extracted movie duration in minutes.
- Converted duration values into integers.
- Plotted a histogram of movie durations.

**Goal:** Analyze movie length distribution on Netflix.

---

### 8. Top Titles by Duration Frequency
- Analyzed frequently occurring title-duration values.
- Visualized the top 10 titles by duration frequency.

**Goal:** Observe notable title-duration patterns.

---

## Key Insights
- Movies outnumber TV Shows on Netflix.
- Drama and International genres dominate the platform.
- The United States is the leading content producer.
- A small group of directors contributes a large portion of titles.
- Most Netflix movies fall within the 90–120 minute range.

---

## How to Run the Project
1. Clone the repository  
2. Install dependencies:
```bash
pip install pandas matplotlib seaborn numpy
```
3. Place `netflix_titles.csv` in the project directory  
4. Run the Python script or Jupyter Notebook  

---

## Learning Outcomes
- Real-world data cleaning experience  
- Handling missing values effectively  
- Creating meaningful visualizations  
- Performing structured EDA for insight generation  

---

## Author
**Deep Roy**  
Aspiring Data Analyst | Python | SQL | Data Visualization
