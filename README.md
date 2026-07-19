# **Airbnb Listings Analysis: Rating Patterns & Distribution (NYC 2012–2022)**

## **📌 Project Overview**
This project analyzes Airbnb listing data in New York City from 2012 to 2022, focusing on rating behavior, listing distribution, and factors influencing guest satisfaction.

The analysis explores how location, review activity, and booking policies relate to listing performance, highlighting gaps between listing popularity and service quality.

---

## **🎯 Problem Statement**
The short-term rental industry has experienced rapid growth, especially in major cities like New York. According to research from Harvard Business School, a 1-point increase in rating can boost revenue by approximately 5–9%.

However, high listing density and strong exposure do not always translate into better guest satisfaction. Inconsistent service quality, operational challenges, and policy decisions may lead to a mismatch between guest expectations and actual experience.

---

## **🛠️ Tools & Technologies**
- Python (Pandas)
- Jupyter Notebook (VS Code)
- Power BI

---

## **❓ Business Questions**
- Are Airbnb listings concentrated in specific areas?
- How does location (borough & neighbourhood) impact listing performance?
- Does the number of reviews influence guest ratings?
- Do cancellation policies affect guest satisfaction?

---

## **📊 Dataset Information**
- **Source:** Airbnb Open Data (NYC)
- **Period:** 2012 – 2022  
- **Rows:** 102,598 (before cleaning)  
- **Columns:** 26

---

## **🧹 Data Cleaning Process**
Key steps performed:
- Standardizing column names and text formatting
- Handling missing values (fill & drop based on context)
- Fixing inconsistent text (e.g., neighbourhood naming)
- Converting incorrect data types (e.g., price to numeric)
- Removing duplicates
- Handling invalid values (e.g., minimum nights, availability)
- Feature engineering (price category, host type, review activity)

---

## **📈 Key Insights**

### **1. Geospatial Quality Mismatch**
Manhattan has the highest listing concentration (42.66%), with Harlem contributing the largest share within the borough (12.47%).  
Despite this, Harlem ranks low in average rating (~3.23), indicating inconsistency in service quality in high-density areas.

---

### **2. Review Saturation Effect**
Listings with high review activity tend to have lower average ratings (~3.17) and a higher proportion of low ratings.  
This suggests operational challenges in maintaining consistent service quality with high guest turnover.

---

### **3. Flexible Policy Trade-off**
Listings with flexible cancellation policies show the lowest average ratings (~3.10) among high-activity listings.  
Frequent booking changes may disrupt operational stability and impact guest experience.

---

## **📌 Conclusion**
High listing volume or popularity does not guarantee better guest satisfaction. Ratings are more influenced by service consistency, operational readiness, and the ability of hosts to meet guest expectations.

Additionally, high review volume reflects diverse guest experiences rather than consistently high satisfaction, while flexible policies do not necessarily improve ratings.

---

## **💡 Recommendations**

- **Review Analysis Optimization**  
  Conduct deeper analysis of guest reviews to identify root causes of low ratings and service gaps.

- **Cancellation Policy Adjustment**  
  Encourage high-traffic listings to adopt more structured cancellation policies (moderate/strict) to improve operational consistency.

- **Host Performance Monitoring**  
  Implement dashboard alerts for declining ratings and provide actionable recommendations to hosts.
