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
**Is there a correlation between certain baby names and specific ethnic groups in the city of New York from 2011-2021?**

**Why it’s important:**  
Exploring the association between baby names and ethnic groups can shed light on cultural traditions and naming conventions within diverse communities. Names often carry significant cultural heritage, and certain names may be predominantly chosen within specific ethnic groups. Understanding these patterns can be valuable for sociological research, marketing strategies, and fostering cultural appreciation. The dataset includes information segmented by sex and ethnic group, making it suitable for this type of analysis.

**Observation 1**
White Non-Hispanic (purple) tends to dominate across most names, especially top-ranking ones.
Hispanic (green) is also highly represented, sometimes being the second-largest ethnic group for a name.
Black Non-Hispanic (yellow) is consistently present across many names but in smaller proportions.
Asian and Pacific Islander groups (blue and orange) appear less frequently and mostly in lower proportions, suggesting some names are less common in those communities.
This order makes sense because it ranks from highest to lowest population by race according to the US Census

**Observation 2**
Ethan, Jacob, and Micheal are the most popular baby names 
They are also all biblical names 
The most popular baby name is ‘Ethan’ and this name was most commonly used by people who identified as Hispanic. This includes years from 2011-2021.
Top names like LUNA, ISABELLA, EMMA, and SOFIA have the highest overall counts, indicating strong popularity across the U.S.
Hispanic and White Non-Hispanic groups make up the majority of counts for most names.
LUNA, CAMILA, and SOFIA show especially high counts among Hispanic individuals.
EMMA, OLIVIA, and AVA are more common among White Non-Hispanic groups.
Some names, like SOFIA and MIA, demonstrate balanced usage across multiple ethnicities, suggesting cross-cultural appeal.
Asian and Pacific Islander and Black Non-Hispanic groups are present but have smaller representation overall.
Name popularity declines steadily from left to right, with the top 10 names significantly more common than those further down the chart.
Names such as esmeralda with origins from spanish and/or latin are more common in hispanic population → possible explanation could be to preserve culture 
From the years 2015-2021, the most common name was ‘Liam’ and again, it was most popularly used by people who identified as Hispanic.



### **Question 2:**  
**Is there a correlation between baby name popularity in New York and major events or celebrities during that time?**

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
