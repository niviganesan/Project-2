# Project-2
# MIST 4610: Group Project 2 - Popular Baby Names

## 🧠 Team Name and Members
**Team Name:** [Insert Your Assigned Team Name from eLC]  
**Team Members:**  
- [Summer Arrington] - [@SummerA100]  
- [Nivi Ganesan] - [@niviganesan]  
- [Rachel Cox] - [@rachellcox]  
- [Katya Tokarev] - [@katyatokarev]
- [Jack Delinsky] - [@JackDelinsky]

---

## 📊 Dataset Description

**Dataset Title:** [Popular Baby Names – Data.gov]  
**Source:** [https://catalog.data.gov/dataset/popular-baby-names](https://catalog.data.gov/dataset/popular-baby-names)  
**Dimensions:**  
- **Rows:** ~200,000+ records  
- **Columns:** 6

**Columns and Data Types:**
- `Year of Birth` (Integer): The year the baby was born
- `Gender` (String): M or F
- `Ethnicity` (String): Ethnic background (e.g., Asian and Pacific Islander, Black Non Hispanic, etc.)
- `Child's First Name` (String): The baby's first name
- `Count` (Integer): Number of babies given that name
- `Rank` (Integer): Ranking of that name within its category

This dataset contains baby name statistics collected by the New York City Department of Health and Mental Hygiene. It tracks name frequency over time by gender and ethnic group.

---

## ❓ Project Questions and Significance

### **Question 1:**  
**How have the most popular baby names changed across different ethnic groups over the past 20 years in New York City?**

**Why it’s important:**  
This question helps us understand how cultural backgrounds influence naming practices in one of the most diverse cities in the U.S. It reflects broader social patterns, including immigration, media influences, and community identity. Tracking name trends by ethnicity offers valuable insight into evolving cultural values and how different groups preserve or adapt traditions.

**Tied to Dataset:**  
The dataset provides `Ethnicity`, `Year of Birth`, `Child's First Name`, and `Count`—perfect for visualizing naming trends over time across different groups.

---

### **Question 2:**  
**Is there a pattern in gender name popularity—are boy names or girl names more likely to remain in the top 10 for multiple consecutive years?**

**Why it’s important:**  
This question explores the idea of naming stability and gender-based cultural tendencies. Are boys' names more rooted in tradition? Are girls’ names more trend-driven? These insights can inform understandings of social norms, identity, and cultural consistency.

**Tied to Dataset:**  
With `Rank`, `Gender`, and `Year of Birth`, we can examine how long names stay at the top. This allows for visualizing stability vs. variability in popular names by gender.

---

## 🛠️ Data Manipulation and Preparation

To prepare the dataset for analysis:
- Filtered out incomplete or invalid records
- Calculated how many years each name remained in the top 10
- Grouped data by ethnicity, gender, and year to create trend comparisons
- Exported summarized tables and pivoted formats for easier Tableau analysis

---

## 📈 Analysis and Results

**Tableau Visualizations Include:**
- Line graphs of top baby names over time by ethnicity
- Bump charts showing rank changes across years
- Bar charts comparing top 10 name retention across genders

**Key Takeaways:**
- Some ethnic groups show more consistency in top names, while others display more year-to-year variation.
- Boys' names often stay in the top 10 longer than girls' names.
- Cultural and media influences (celebrities, TV shows, etc.) play a role in sudden popularity spikes.

---

## 📦 Tableau Packaged Workbook

The Tableau Packaged Workbook file (`.twbx`) is included in this repository:  
👉 [Link to the Tableau `.twbx` file here once uploaded]

---

## 📚 Citations and References

- U.S. Government Open Data – Popular Baby Names  
  [https://catalog.data.gov/dataset/popular-baby-names](https://catalog.data.gov/dataset/popular-baby-names)
- Tableau Software  
  [https://www.tableau.com](https://www.tableau.com)

---
