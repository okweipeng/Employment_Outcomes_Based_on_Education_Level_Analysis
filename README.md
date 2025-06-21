# Employment Outcomes Based on Education/College Major Analysis

---

## Research Question  
How does college degree attainment influence employment rates and job prospects, and what are the differences in employment outcomes between college graduates and non-graduates?

---

## Overview  
This project analyzes employment and wage data to explore the relationship between education levels—especially college degrees—and employment outcomes in the United States. 

---

## Data Sources  
The analysis uses several datasets, including:  
- `all-ages.csv`  
- `grad-students.csv`  
- `majors-list.csv`  
- `recent-grads.csv`  
- `women-stem.csv`  
- `wages_by_edu.csv`

**Files used via Github:** (Section ~ college-majors) 

Source: https://github.com/fivethirtyeight/data/tree/master/college-majors 

*Credit: Bencasselman*

**Files used via Kaggle:**

Source: https://www.kaggle.com/datasets/asaniczka/wages-by-education-in-the-usa-1973-2022
  
---

## Key Analyses & Visualizations  

### 1. Wages by Education Level and Gender (1973 - 2022)  
- Line plots comparing wages over time by education level, split by gender.  
- Different line styles and markers differentiate men (solid lines) and women (dashed lines with markers).  
- Uses a color-blind-friendly palette for accessibility.

### 2. Employment Type Among Recent Graduates by Major Category (2022)  
- Merges recent graduates and graduate students datasets on major categories.  
- Calculates part-time and full-time employment percentages by major category.  
- Visualized with a heatmap to highlight employment type distribution.

### 3. Wages by Major Category  
- Merges recent graduates data with major category list.  
- Calculates median wages for each major category.  
- Bar plot visualizes median wage differences across majors using a ‘viridis’ color palette.

---

## Key Findings  

- **Wages & Education:** Higher education levels generally correlate with higher wages. Men tend to have solid-line wage trends, while women’s wages are tracked with markers for clarity.  
- **Employment Type:**  
  - Top full-time employment majors: Business (83.4%), Engineering (81.8%), Computer & Mathematics (79.6%).  
  - Top part-time employment majors: Arts (35.6%), Humanities & Liberal Arts (33.9%), Biology & Life Science (32.7%).  
- **Wages by Major:**  
  - Highest earners: Engineering ($57,000), Computer Science & Math ($45,000), Business ($40,000).  
  - Lowest earners: Social Work and Psychology ($30,000), Arts ($30,750).  
  - Moderate earners: Physical Sciences, Social Sciences, Biology & Life Sciences ($36,000 to $39,500).  

---

## Conclusion  
This project sheds light on how college degree attainment and choice of major influence employment rates, job types, and wages. While higher education generally leads to better employment outcomes, the data also highlights important differences across fields of study and gender. 

---
