# Project-2
# MIST 4610: Group Project 2 - Popular Baby Names

## 🧠 Team Name and Members

**Team Name:** Sp25_21482_Group2 
          
     
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
- **Rows:** 69,000 rows  
- **Columns:** 6

**Columns and Data Types:**
- `Year of Birth` (Integer): The year the baby was born
- `Gender` (String): M or F
- `Ethnicity` (String): Ethnic background (e.g., Asian and Pacific Islander, Black Non Hispanic, etc.)
- `Child's First Name` (String): The baby's first name
- `Count` (Integer): Number of babies given that name
- `Rank` (Integer): Ranking of that name within its category

![image](https://github.com/user-attachments/assets/b960ee40-4db0-4360-ac72-d35e51b8dfb4)


This dataset contains baby name statistics collected by the New York City Department of Health and Mental Hygiene. It tracks name frequency over time by gender and ethnic group.

---

## 🛠️ Data Manipulation and Preparation

- Added a calculation titled UPPER to combine the names that were added in twice, once for lowercase and once for uppercase (total count for one name)
UPPER([Child's First Name])
- Changed Year of Birth from Integer to DATE as it was intended to be analyzed yearly,
Clicked the icon to the left of year of birth and selected date/time (icon looks like a calendar now),
Time of birth was not relevant to us, only the year

![image](https://github.com/user-attachments/assets/2dca71a5-7a3c-4d54-b746-677591687fcf)

---

## ❓ Project Questions and Significance

### **Question 1:**  
**Is there a correlation between certain baby names and specific ethnic groups in the city of New York from 2011-2021?**

**Why it’s important:**  
Exploring the association between baby names and ethnic groups can shed light on cultural traditions and naming conventions within diverse communities. Names often carry significant cultural heritage, and certain names may be predominantly chosen within specific ethnic groups. Understanding these patterns can be valuable for sociological research, marketing strategies, and fostering cultural appreciation. The dataset includes information segmented by sex and ethnic group, making it suitable for this type of analysis.

**Observation 1**
-White Non-Hispanic (purple) tends to dominate across most names, especially top-ranking ones.
-Hispanic (green) is also highly represented, sometimes being the second-largest ethnic group for a name.
-Black Non-Hispanic (yellow) is consistently present across many names but in smaller proportions.
-Asian and Pacific Islander groups (blue and orange) appear less frequently and mostly in lower proportions, suggesting some names are less common in those communities.
-This order makes sense because it ranks from highest to lowest population by race according to the US Census

**Observation 2**
-Ethan, Jacob, and Micheal are the most popular baby names 
-They are also all biblical names 
-The most popular baby name is ‘Ethan’ and this name was most commonly used by people who identified as Hispanic. This includes years from 2011-2021.
-Top names like LUNA, ISABELLA, EMMA, and SOFIA have the highest overall counts, indicating strong popularity across the U.S.
-Hispanic and White Non-Hispanic groups make up the majority of counts for most names.
-LUNA, CAMILA, and SOFIA show especially high counts among Hispanic individuals.
-EMMA, OLIVIA, and AVA are more common among White Non-Hispanic groups.
-Some names, like SOFIA and MIA, demonstrate balanced usage across multiple ethnicities, suggesting cross-cultural appeal.
-Asian and Pacific Islander and Black Non-Hispanic groups are present but have smaller representation overall.
-Name popularity declines steadily from left to right, with the top 10 names significantly more common than those further down the chart.
-From the years 2015-2021, the most common name was ‘Liam’ and again, it was most popularly used by people who identified as Hispanic.
-Names such as esmeralda with origins from spanish and/or latin are more common in hispanic population → possible explanation could be to preserve culture 

![image](https://github.com/user-attachments/assets/0495e59c-2225-47f8-8364-6b3deb01abac)

--

### **Question 2:**  
**Is there a correlation between baby name popularity in New York and major events or celebrities during that time?**

**Why it’s important:**  
This analytical question explores whether external cultural influences, such as major news events, popular media, or celebrity prominence, have a measurable impact on the frequency of specific baby names over time. By analyzing trends in baby name popularity and comparing them to timelines of significant events (e.g., a celebrity becoming widely known, a movie release, a political figure rising in prominence), the analysis seeks to uncover patterns of cause-and-effect or influence in naming behavior.

**Observation**
-Zendaya (name) was super popular in 2013-2014 → KC Undercover, Zapped, Shake It Up, Red Carpets
-Zuri (name) grew in popularity from 2011-2015 then decreased in 2016 went back up from 2017-2018 then decreased in 2019 then dramatically increased in 2020 
-Alessandro popular every 2 years it seems for 2 years 2015-2016 then none in 2017 then again in 2018-2019 and none in 2020 then back in 2021
-Ethan was overall the most popular baby name, with 22,149 babies. This was most used by people of Hispanic Ethnicity. 
-Biblical names popular with white and hispanic due to large christian populations 

![image](https://github.com/user-attachments/assets/ec4cc66d-6eba-4962-bc98-feea6fecaf9c)

---

## 📈 Analysis and Results

**Question 1**
Overall, the data reveals how name choices can reflect cultural identity, familial heritage, and community norms:
Hispanic Names: Luna, Camila, Isabella, Sofia — all of Latin/Spanish origin, reflecting cultural preservation.
White Non-Hispanic Names: Emma, Olivia, Ava are most common.
Cross-Ethnic Popularity: Sofia and Mia appear across multiple groups.
Asian/Pacific Islander Names: Ethan, Jayden, Ryan, Kevin, Chloe, Olivia, Sophia — likely influenced by Western naming norms. The dataset may not account for the native names given to babies that reflect their culture. 


**Question 2**
Our analysis shows a clear link between pop culture phenomena and baby name trends over the last decade:
Zendaya: Name spiked in 2013–2014 during peak TV popularity (KC Undercover, Zapped)
Zuri: Rose after Jessie aired (2011), surged again in 2020 (due to pandemic rewatching)
Insight: Media and celebrities influence baby name trends
These examples highlight how major cultural moments can directly impact naming trends. Parents may be inspired by beloved characters or celebrities who represent traits they admire or find aspirational.


**Conclusion**
Our analysis of New York City baby names (2011–2021) reveals strong correlations between name popularity and both ethnic background and cultural events.
Names like Luna, Sofia, and Ethan highlight how heritage and cultural preservation influence naming within different communities.
Trends also reflect media and celebrity impact, with names such as Zendaya and Zuri showing rises in popularity during periods of major pop culture presence.
These insights can inform future research in sociology, marketing, and cultural studies, as names serve as a reflection of both identity and societal trends

---

## 📚 Citations and References

- U.S. Government Open Data – Popular Baby Names  
  [https://catalog.data.gov/dataset/popular-baby-names](https://catalog.data.gov/dataset/popular-baby-names)
- Tableau Software  
  [https://www.tableau.com](https://www.tableau.com)

---
