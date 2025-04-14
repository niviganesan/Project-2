# Project-2
# MIST 4610: Group Project 2 - Popular Baby Names

## 🧠 Team Name and Members
**Team Name:** [Insert Your Assigned Team Name from eLC]  
**Team Members:**  
- Summer Arrington - [@SummerA100](https://github.com/SummerA100) 
- Nivi Ganesan - [@niviganesan](https://github.com/niviganesan)
- Rachel Cox - [@rachellcox](https://github.com/rachellcox) 
- Katya Tokarev - [@katyatokarev](https://github.com/katyatokarev)
- Jack Delinsky - [@JackDelinsky](https://github.com/JackDelinsky)

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
**Is there a correlation between certain baby names and specific ethnic groups?**

**Why it’s important:**  
Exploring the association between baby names and ethnic groups can shed light on cultural traditions and naming conventions within diverse communities. Names often carry significant cultural heritage, and certain names may be predominantly chosen within specific ethnic groups. Understanding these patterns can be valuable for sociological research, marketing strategies, and fostering cultural appreciation. The dataset includes information segmented by sex and ethnic group, making it suitable for this type of analysis.

---

### **Question 2:**  
**Is there a correlation between baby name popularity and major events or celebrities during that time?(Analytical)**

**Why it’s important:**  
This analytical question explores whether external cultural influences, such as major news events, popular media, or celebrity prominence, have a measurable impact on the frequency of specific baby names over time. By analyzing trends in baby name popularity and comparing them to timelines of significant events (e.g., a celebrity becoming widely known, a movie release, a political figure rising in prominence), the analysis seeks to uncover patterns of cause-and-effect or influence in naming behavior.

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
