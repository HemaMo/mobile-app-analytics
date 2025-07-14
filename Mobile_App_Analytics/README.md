
#  Mobile App Analytics – User Behavior & Engagement Analysis

##  Project Overview

This project presents a full analytical case study for a mobile application aiming to understand **user behavior**, evaluate **engagement patterns**, and generate **data-driven insights** to improve the app's performance and conversion rates.

---

##  Problem Statement

A company is looking to:
- Understand user engagement patterns
- Identify drop-off points and exit pages
- Measure the impact of user behavior on conversions
- Improve product decisions based on behavioral insights

---

##  Datasets Used

- **Users Dataset**
  - UserID, Age, Gender, Device Type, Location
- **Sessions Dataset**
  - Session duration, Clicks, Scrolls, Likes, Pages Visited, Exit Page, Network Speed, Conversion

---

##  Data Cleaning & Preparation

- Filled missing values (e.g., most frequent `ExitPage`)
- Removed outliers using IQR on `SessionDuration` and `NetworkSpeed`
- Handled infinite values resulting from division operations

---

##  Feature Engineering

New features added to enhance behavioral insight:
- `ClicksPerPage`, `ScrollsPerMinute`, `ClickRate`
- `EngagementScore` (weighted metric from clicks, scrolls, and likes)
- Binary flags like `IsLongSession`, `IsHighSpeed`
- Click behavior categorization (`ClickLevel`)

---

##  Exploratory Data Analysis (EDA)

Conducted detailed visual analysis:
- Distributions of duration, clicks, scrolls
- Correlation heatmap among behavior metrics
- Top exit pages
- Conversion vs engagement patterns

---

##  Key Insights

- High engagement users show higher conversion probabilities
- Exit rates concentrated in specific pages → UI/UX optimization needed
- Engagement score is a strong signal of conversion likelihood

---

##  Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy, Seaborn, Matplotlib

---

##  Future Enhancements

- Apply Machine Learning models to predict conversion
- Segment users based on behavioral clusters
- Run A/B testing on pages with high exit rates

---

##  Author

**Ebrahim Mohamed**

-  [LinkedIn](https://www.linkedin.com/in/ebrahim-mohamed-655b81323)
-  GitHub: [HemaMo](https://github.com/HemaMo)

---

##  If you found this useful...

Please consider giving it a ⭐ on GitHub or sharing it on LinkedIn!
