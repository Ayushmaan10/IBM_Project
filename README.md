# IBM_Project


# HR Employee Attrition EDA

This project performs an Exploratory Data Analysis (EDA) on the **HR Employee Attrition** dataset to identify key factors contributing to employee turnover. The analysis provides actionable business insights and recommendations to improve retention.

## 📊 Project Overview

The goal of this analysis is to understand *why* employees leave the company. We examine various factors ranging from work conditions and compensation to career progression and demographics.

**Dataset:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`

## 🔑 Key Findings & Recommendations

The analysis is categorized into four main areas:

### 1. Work Conditions ("Burnout" Factors)
*   **Overtime:**
    *   **Insight:** Employees working overtime have a **30.5%** attrition rate, compared to **10.4%** for those who don't.
    *   **Recommendation:** Investigate workload distribution to prevent burnout.
*   **Commute Distance:**
    *   **Insight:** Leavers commute an average of **10.6 km**, while stayers commute **8.9 km**.
    *   **Recommendation:** Consider remote work options or shuttle services for employees living >15km away.
*   **Business Travel:**
    *   **Insight:** Frequent travelers have a **24.9%** attrition rate, significantly higher than rare/non-travelers.
    *   **Recommendation:** Rotate travel responsibilities to reduce fatigue.

### 2. Financial Incentives
*   **Monthly Income:**
    *   **Insight:** Median income for Leavers is **$3,202** vs. **$5,204** for Stayers. Low pay is a major factor.
    *   **Recommendation:** Review market competitiveness for roles falling below the median income of stayers.
*   **Stock Options:**
    *   **Insight:** Employees with **NO** stock options have a high attrition rate of **24.4%**. Those with options have a rate of **9.9%**.
    *   **Recommendation:** Consider granting at least Level 1 stock options to a broader base of employees.
*   **Salary Hike:**
    *   **Insight:** The minimum attrition rate (**5.6%**) occurs at a salary hike of **25%**.
    *   **Recommendation:** Ensure high-potential employees consistently receive raises in the optimal range.

### 3. Career Progression
*   **Promotion Stagnation:**
    *   **Insight:** Employees not promoted in **5+ years** have higher attrition compared to those promoted recently (<2 years).
    *   **Recommendation:** Implement a "Step-Up" program for employees stuck at the same level for 4+ years.
*   **Manager Stability:**
    *   **Insight:** The highest risk of attrition occurs in **Year 0** with a new manager.
    *   **Recommendation:** HR should support teams heavily during the first 6 months of a manager change.
*   **Job Level:**
    *   **Insight:** Entry-level employees (Level 1) have a massive attrition rate, whereas Executives (Level 5) rarely leave.
    *   **Recommendation:** Focus retention strategies on "Career Pathing" for Level 1 employees.

### 4. Demographics
*   **Age:**
    *   **Insight:** "Young Talent" (18-25) leaves at a rate of **34.8%**, while mid-career (36-45) attrition is only **9.2%**.
    *   **Recommendation:** Implement a "Young Leaders" mentorship program to engage Gen Z employees early.

## 🛠️ Tools Used
*   **Python**
*   **Pandas** (Data Manipulation)
*   **Matplotlib & Seaborn** (Data Visualization)

