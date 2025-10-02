# 🍽️ Online Food Ordering Behavior Dashboard

---

## 📊 Project Overview
An interactive **Power BI dashboard** analyzing **customer demographics, ordering patterns, and behavioral insights** for online food services. This analysis helps restaurants and delivery platforms understand their customer base and optimize business strategies.  

- **Dataset Source:** Kaggle  
- **Tool Used:** Microsoft Power BI  
- **Records Analyzed:** 388 customer entries  

---

## 📁 Dataset Columns & Description

| Column Name               | Description                            | Type         | Key Insights                                   |
|----------------------------|----------------------------------------|--------------|-----------------------------------------------|
| Age                        | Customer age in years                  | Numerical    | Youth-dominated market (Avg: 24.63 years)    |
| Gender                     | Male/Female distribution               | Categorical  | Gender-based preference analysis              |
| Marital Status             | Single/Married/Prefer not to say       | Categorical  | Lifestyle impact on ordering                  |
| Occupation                 | Professional background                | Categorical  | Student-dominated (60%+)                      |
| Monthly Income             | 5 income brackets                       | Categorical  | Income vs ordering correlation                |
| Educational Qualifications | Education levels                        | Categorical  | High education correlation                     |
| Family Size                | Number of family members               | Numerical    | Family dining preferences                      |
| Latitude/Longitude         | Geographic coordinates                 | Numerical    | Location-based analysis                        |
| Pin Code                   | Area codes                             | Categorical  | Service zone optimization                      |
| Output                     | Ordering decision (Yes/No)             | Categorical  | 22.42% conversion rate                          |
| Feedback                   | Customer satisfaction                   | Categorical  | Service quality insights                        |

---

## 🎯 Business Questions & Insights

### 👥 Customer Demographics Analysis
**Q1: Who are our primary customers in terms of age and occupation?**  
- Predominantly young students (**Avg. Age: 24.63 years**)  
- Students: 62%, Employees: 22%, Self-Employed: 11%  

**Q2: Typical family size?**  
- Average: 3.28 members  
- Medium-sized families show highest ordering propensity  

**Q3: Education level of customers?**  
- Graduates: 42%  
- Postgraduates: 38%  
- Ph.D: 12%  

---

### 💰 Income & Spending Behavior
**Q4: How does income level affect ordering?**  
- “No Income” and “Below Rs. 10,000” groups order most frequently  
- Price sensitivity and convenience drive ordering  

**Q5: Which income group orders the most?**  
- Students (“No Income”) lead, followed by Rs. 10,001–25,000 bracket  

**Q6: Correlation between family size and ordering frequency?**  
- Medium families (3–4 members) have highest ordering propensity  
- Single-person households order less frequently but consistently  

---

### 📍 Geographical & Service Analysis
**Q7: Customer concentration?**  
- High density in urban educational and commercial zones  

**Q8: Occupation influence on ordering?**  
- Students: frequent, smaller orders  
- Employees & Self-Employed: fewer but higher-value orders  

---

### 📈 Business Performance
**Q9: Online ordering percentage?**  
- Conversion Rate: 22.42% (**87 of 388 customers**)  

**Q10: Feedback trends across segments?**  
- Positive feedback dominates across all segments  
- Certain occupation groups show higher satisfaction  

---

## 📊 Dashboard Sections & Visualizations

### 1️⃣ Demographics Overview
**Primary Metrics:**  
- Average Age: 24.63 years  
- Average Family Size: 3.28 members  
- Total Respondents: 388  

**Key Visualizations:**  
- **Age Distribution Pyramid**: Youth-dominated (18–28 years)  
- **Education Level Breakdown**: Graduate 42%, Postgraduate 38%, Ph.D 12%  
- **Occupation Distribution**: Student 62%, Employee 22%, Self-Employed 11%  
- **Marital Status Analysis**: Single 78%, Married 20%, Prefer not to say 2%  

---

### 2️⃣ Income & Ordering Behavior
**Conversion Metrics:**  
- ✅ Positive Orders: 87 (22.42%)  
- ❌ No Orders: 301 (77.58%)  

**Key Visualizations:**  
- **Income Bracket Analysis**: 5-tier income category performance  
- **Ordering Decision by Income**: Clear income-based patterns  
- **Family Size Impact Chart**: 5 family size categories vs ordering frequency  
- **Occupation vs Ordering**: Professional background influence  

---

### 3️⃣ Geographic & Feedback Analysis
**Location Intelligence:**  
- Pin Code Concentration: High-density areas  
- Regional Distribution: Urban vs suburban  
- Service Zone Mapping: Optimal delivery areas  

**Customer Satisfaction:**  
- Feedback by Occupation  
- Gender-based Feedback  
- Overall Positive/Negative feedback distribution  

---

## 🔍 Major Insights & Patterns

### 🎓 Education & Professional Insights
- 62% of customers are students  
- 92% have Graduate level or higher education  
- Employees show different ordering times and preferences  

### 💵 Economic Behavior Patterns
- “No Income” group (students) orders frequently despite budget constraints  
- Middle-income groups (Rs. 10,001–25,000) show balanced frequency and order value  

### 🏠 Family Dynamics & Ordering
- Optimal family size: 3–4 members  
- Single households: consistent but less frequent ordering  
- Large families: lower frequency but larger order values  

### 📊 Performance & Conversion
- Market potential: 22.42% conversion rate  
- 77.58% non-ordering customers represent untapped market  

---

## 💡 Strategic Recommendations

### Marketing
- 🎯 Target student campaigns near universities  
- 🍱 Family meal packages for 3–4 member families  
- 🎁 Loyalty programs for employed customers  

### Business Growth
- 🌍 Geographic expansion to high-potential pin codes  
- 💰 Income-bracket-specific pricing and packages  
- 🔑 Focus on high-conversion demographic segments  

### Operations
- 🚚 Delivery zone optimization  
- 📦 Inventory aligned with family size and occupation  
- ⭐ Quality improvement based on feedback patterns  

### Customer Experience
- 🎁 Personalized offers based on occupation and family size  

---

## 🛠️ Technical Implementation

**Data Processing Steps:**  
1. Data Cleaning: Handling missing values and inconsistencies  
2. Category Creation: Income brackets, family size groups, age segments  
3. Geographic Mapping: Pin code to area mapping  
4. Segment Creation: Demographic and behavioral segments  

**Power BI Features Used:**  
- Interactive slicers for dynamic filtering  
- Cross-chart filtering  
- KPI cards for key metrics  
- Geographic visualization for location analysis  
- Drill-through for detailed analysis  

---

## 📸 Dashboard Navigation Guide
1. **Demographics Overview**  
   - Understand customer base composition  
   - Identify key patterns  

2. **Income & Behavior Analysis**  
   - Apply income filters to see segment performance  
   - Analyze ordering patterns by family size  

3. **Geographic Analysis**  
   - View customer concentration by pin code  
   - Identify service expansion opportunities  

4. **Feedback Review**  
   - Analyze satisfaction across segments  
   - Track service quality metrics  

---
## 📊 Dashboard Visuals

Click the images below to view the full dashboards:

[![Demographics Overview](https://img.shields.io/badge/Demographics-Overview-blue?style=for-the-badge)](https://github.com/shivanisyal09/Online-Food-Order-Analysis/blob/main/Demographics%20Overview.png)

[![Ordering Behavior & Income](https://img.shields.io/badge/Ordering-Behavior_&_Income-green?style=for-the-badge)](https://github.com/shivanisyal09/Online-Food-Order-Analysis/blob/main/Ordering%20Behavior%20%26%20Income.png)

[![Customer Feedback & Location](https://img.shields.io/badge/Customer-Feedback_&_Location-orange?style=for-the-badge)](https://github.com/shivanisyal09/Online-Food-Order-Analysis/blob/main/Customer%20Feedback%20%26%20Location.png)

---
