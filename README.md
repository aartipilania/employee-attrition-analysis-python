# employee-attrition-analysis-python
# Employee Attrition Analysis using Python

## Project Overview

Employee attrition is one of the most important challenges faced by organizations, as high turnover leads to increased recruitment costs, loss of organizational knowledge, and reduced productivity.

The objective of this project is to identify the factors associated with employee attrition and uncover actionable insights that can help improve employee retention.

---

## Dataset Preparation

The analysis began by:

* Importing the employee attrition dataset
* Exploring the dataset structure
* Checking for missing values and data quality issues
* Calculating the overall attrition rate

### Key Finding

The overall employee attrition rate was approximately **16%**, indicating that around one out of every six employees had left the organization.

---

## Department-wise Attrition Analysis

Attrition rates were analyzed across departments to identify areas with higher employee turnover.

### Findings

* **Sales Department** recorded the highest attrition rate (**20.63%**)
* **Human Resources** followed with an attrition rate of **19.05%**
* **Research & Development** showed the lowest attrition rate (**13.84%**)

### Insight

Sales and HR departments may require additional retention strategies compared to Research & Development.

---

## Attrition vs Overtime

The relationship between overtime and employee attrition was explored.

### Findings

* Employees working overtime had an attrition rate of **30.53%**
* Employees not working overtime had an attrition rate of **10.44%**

### Insight

Employees who work overtime are nearly three times more likely to leave the organization, suggesting workload and work-life balance may significantly influence employee retention.

---

## Attrition by Job Role

Attrition rates were compared across different job roles.

### Findings

* **Sales Representatives** exhibited the highest attrition rate (**39.76%**)
* **Human Resources** and **Laboratory Technicians** also showed relatively high attrition rates
* **Managers** and **Research Directors** demonstrated very low attrition rates

### Insight

Junior and operational roles appear more vulnerable to employee turnover than senior leadership positions.

---

## Income and Attrition Analysis

Employees were grouped into income bands to evaluate the relationship between compensation and attrition.

### Findings

* Attrition was highest among employees in lower income groups
* Employees aged **18–25** were highly concentrated within lower income bands and experienced the highest attrition levels

### Insight

Compensation appears to influence attrition, particularly among younger employees.

---

## Income Distribution Across Job Roles

To better understand the relationship between income and attrition, income distributions were analyzed across job roles.

### Findings

* High-attrition job roles such as:

  * Sales Representatives
  * Laboratory Technicians
  * Human Resources

  were primarily concentrated within lower income bands.

* However, many **Research Scientists** also belonged to similar income bands while exhibiting lower attrition rates.

### Insight

Income contributes to attrition but cannot fully explain employee turnover on its own. Other factors also play a significant role.

---

## Job Role, Overtime, and Attrition

A deeper analysis was conducted to determine whether high-attrition job roles also experienced higher levels of overtime.

### Findings

* Research Scientists reported substantial overtime but did not exhibit the highest attrition.
* Within high-attrition job roles, employees who worked overtime consistently showed higher attrition than those who did not.

Examples:

* Sales Representatives:

  * Overtime = Yes → Significantly higher attrition
  * Overtime = No → Lower attrition

* Laboratory Technicians:

  * Overtime = Yes → Higher attrition
  * Overtime = No → Lower attrition

### Insight

Overtime alone does not cause attrition. However, when combined with lower-paying job roles, overtime appears to increase the likelihood of employee turnover.

---

## Attrition by Age Group

Employee attrition was analyzed across age bands.

### Findings

* Younger employees (18–25) experienced the highest attrition rates.
* Attrition decreased across middle-age groups.
* A secondary increase in attrition was observed among employees aged 45–55.

### Insight

Employee turnover appears to be influenced by career stage, with both early-career and late-career employees showing elevated attrition levels.

---

## Monthly Income Analysis

Average monthly income was compared between employees who stayed and employees who left.

### Findings

Employees who left the organization had lower average monthly incomes compared to employees who remained.

### Insight

Lower compensation levels may contribute to employee turnover.

---

## Years at Company Analysis

A boxplot was used to compare years at company against attrition status.

### Findings

* Employees who left typically had a median tenure of approximately **3 years**
* Several outliers existed, including employees with very long tenures who still left the organization

### Insight

The risk of attrition appears highest during the early years of employment.

---

## Correlation Analysis

A correlation heatmap was generated using key numerical variables:

* Age
* Monthly Income
* Total Working Years
* Years at Company
* Distance from Home
* Attrition

### Findings

* Attrition showed weak negative correlations with:

  * Age
  * Monthly Income
  * Total Working Years
  * Years at Company

* Strong positive correlations existed among:

  * Monthly Income and Total Working Years
  * Age and Total Working Years

### Insight

Attrition is not driven by a single numerical factor. Instead, employee turnover appears to result from the combined influence of age, income, experience, overtime, and job role.

---

# Key Business Recommendations

Based on the analysis, the following actions may help reduce employee attrition:

1. Monitor overtime and workload in high-risk job roles.
2. Review compensation structures for lower-income positions.
3. Develop retention programs targeting younger employees.
4. Focus retention efforts on Sales Representatives, Laboratory Technicians, and HR employees.
5. Provide career development opportunities during the first few years of employment.

---

# Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Conclusion

The analysis revealed that employee attrition is influenced by multiple interconnected factors. Overtime, lower income, job role, age, and tenure all contribute to employee turnover. Among these factors, overtime and specific job roles emerged as particularly strong indicators of attrition risk. Organizations can leverage these insights to design targeted retention strategies and improve workforce stability.

