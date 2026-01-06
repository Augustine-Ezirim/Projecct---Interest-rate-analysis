# Interest Rate Differences Between Red and Blue States (2023)

## Project Overview
This project analyzes whether average interest rates differ between U.S. states classified as **Red** or **Blue** based on political alignment. Using state-level interest rate data from 2023, the analysis applies statistical methods to evaluate whether observed differences are statistically significant.

The project demonstrates practical skills in **data preparation, exploratory data analysis (EDA), and hypothesis testing** using Python.

---

## Objectives
- Compare average interest rates between Red and Blue states  
- Determine whether any observed difference is statistically significant  
- Practice data cleaning, integration, and statistical analysis techniques  

---

## Data Description
- **Source:** Excel workbook containing multiple sheets of state-level interest rate data for 2023  
- **Granularity:** State-level observations  
- **Key Variables:**
  - State
  - Interest Rate
  - Political Alignment (Red or Blue)

Multiple sheets were combined into a single standardized dataset to ensure consistency and enable analysis.

---

## Methodology
1. **Data Preparation and Cleaning**
   - Loaded multiple Excel sheets
   - Concatenated datasets into a unified structure
   - Standardized interest rate values and handled formatting issues

2. **State Classification**
   - States were categorized as Red or Blue based on political alignment

3. **Exploratory Data Analysis**
   - Summary statistics by political group
   - Visual comparisons of interest rate distributions

4. **Statistical Analysis**
   - Independent two-sample t-test
   - Significance level set at 5%

---

## Key Findings
- The consolidated dataset enabled a direct comparison of interest rates across political groups.
- Exploratory analysis showed observable differences in interest rate distributions between Red and Blue states.
- The t-test results indicate that the difference in mean interest rates is **statistically significant** at the 5% level.


---

## Conclusion
This analysis evaluates whether political alignment is associated with differences in state-level interest rates. While the statistical results suggest **evidence** of a meaningful difference between Red and Blue states, the findings do not imply causality. Interest rates are influenced by numerous economic and regional factors not captured in this analysis.

Overall, the project demonstrates applied skills in data cleaning, integration, exploratory analysis, and hypothesis testing using Python.

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

---

## Potential Extensions
- Incorporate economic control variables (income, population, regional indicators)
- Analyze multiple years to identify trends over time
- Apply regression analysis for deeper inference

---

## Author
Augustine Ezirim  
MS in Business Analytics

