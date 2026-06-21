# Global Data Breach Analysis

## Project Overview

This project analyzes historical global data breach incidents to identify industry risk patterns, common attack methods, and trends in breach severity over time.

The analysis focuses on understanding:

- How data breaches occur
- Which industries are most affected
- How breach impact has evolved over time

---

## Dataset

**Dataset:** Global Data Breach Incidents

- 520 breach incidents
- 15 features
- Time period: 2004–2025

Key variables used:

- Organisation
- Sector
- Method
- Records Lost
- Date
- Year

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Google Colab

---

## Data Preparation

The dataset was cleaned and standardized by:

- Standardizing column names
- Converting text fields to lowercase
- Converting dates to datetime format
- Cleaning sector and attack method categories
- Checking for missing values and duplicates

---

## Visualizations

### 1. Attack Methods Across Industries (Heatmap)

Analyzes the relationship between attack methods and industry sectors.

**Key Insight:**  
Hacking is the most common attack method across nearly all industries.

---

### 2. Industry Share of Exposed Records (Treemap)

Visualizes the distribution of exposed records across industry sectors.

**Key Insight:**  
Web, government, and telecommunications sectors account for the largest volume of exposed records.

---

### 3. Global Data Breach Impact Over Time (Bubble Chart)

Shows breach incidents over time based on the number of records exposed.

**Key Insight:**  
Large-scale breaches have become more severe, with several incidents exposing hundreds of millions of records.

---

## Key Findings

- Hacking remains the dominant breach method across industries.
- Web organizations account for the highest volume of exposed records.
- Government and telecommunications sectors also contribute significantly to total exposure.
- Data breaches have increased in severity over time.
- A small number of incidents account for a large share of compromised records.

---

## Conclusion

The analysis reveals that data breaches continue to pose significant risks across industries. Web, government, and telecommunications organizations experience the greatest exposure, while hacking remains the primary attack method. The increasing scale of breach incidents highlights the importance of strong cybersecurity controls, continuous monitoring, and effective incident response strategies.


## Author

**Nidhi Rawal**  
Master of Science in Data Science  
Regis University
