### HR ATTRITION CLASS PROJECT

## COMPANY HUMAN RESOURCE ATTRITION 

### ABSTRACT

**This data analysis project focuses on understanding and forecasting employee attrition within a company. Employee attrition, or 
the rate of employee turnover, can have significant financial and operational impacts, making it crucial for companies to identify
and address its root causes. This project aims to analyze various employee-related data to uncover key drivers of attrition and 
predict future turnover trends.**

**Using historical workforce data—including demographics, job roles, tenure, salary, and exit interview responses—the analysis will 
employ data preprocessing, exploratory data analysis (EDA), and machine learning models to identify patterns associated with attrition.
Power BI model will be used to narrow down the analysis reports.**

**The findings will highlight critical factors influencing attrition, such as job satisfaction, compensation, and career progression
opportunities. The project will also provide actionable recommendations to help reduce turnover, improve employee retention, and 
optimize talent management. Ultimately, this analysis aims to equip the company with data-driven insights to foster a stable, engaged, 
and productive workforce.**

## INTRODUCTION 

**Employee attrition, or the rate at which employees leave a company, is a critical metric for businesses. High attrition rates can signal 
issues within an organization, such as employee dissatisfaction, lack of career growth opportunities, or inadequate compensation. 
Understanding and addressing the factors driving attrition can help a company retain its talent, reduce recruitment and training costs, 
and maintain a productive workforce.**

## OBJECTIVE 

**The purpose of this data analysis report is to project employee attrition by examining patterns and trends within the company's workforce data. 
Through this analysis, we aim to identify factors contributing to attrition, predict future attrition rates, and suggest actionable recommendations 
to mitigate high turnover.**

**The analysis involves reviewing historical employee data, such as:**

* **Demographics: Age, gender, marital status,  etc.**

* **Employment Factors: **Department, tenure, salary, job satisfaction, performance ratings, and career growth opportunities.**

* **Exit Interviews and Surveys: **Insights into reasons for leaving, feedback on company culture, and employee engagement.**


## METHOODLOGY

1. **Data Collection: We will gather internal HR data, including demographic information, job history, salary details, and exit interview responses.**


2. **Data Preprocessing: This involves cleaning the data to address inconsistencies, missing values, and outliers that could skew the analysis.**


3.  **Exploratory Data Analysis (EDA): EDA will uncover trends and patterns in the dataset. Visualization tools, such as bar charts,**
     
4. **histograms, and scatter plots, will help us understand correlations between attrition and various factors.**


5.  **Predictive Modeling: Using machine learning algorithms, such as logistic regression, decision trees, and random forests,**
    
6.  **We will build models to predict the likelihood of an employee leaving.**


7. **Validation and Testing: We’ll split the dataset into training and test sets to validate model accuracy and ensure reliable predictions.**



# #EXPECTED OUTCOME

**The report will deliver insights on:**

* **Attrition Drivers: Factors like low job satisfaction, long working hours, poor management, or limited growth opportunities.

**Employee Segments at Risk: Identifying high-risk groups based on demographics, job roles, or tenure.**

* Attrition Rate Forecast: **A projection of future attrition rates if current trends continue.**

* **Recommendations: **Strategies for HR to improve employee retention, such as policy changes, enhanced**
** training programs, and better compensation packages.**


## Benefits of Analysis

* **With a clear understanding of attrition patterns, the company can:**

* **Optimize Talent Management: Proactively address factors leading to turnover.**

* **Enhance Employee Engagement: **Develop initiatives that improve job satisfaction and employee loyalty.**

* C**ost Savings: Lower recruitment, hiring, and training costs by retaining more employees.**

 Strategic Planning: **Use attrition forecasts to plan workforce needs and ensure business continuity.**


**This data-driven approach to understanding and managing employee attrition will help the company retain key 
talent, foster a positive work environment, and support long-term growth.**

## DATA DESCRIPTION
**Data Description for Human Resources Details**

**This dataset contains employee data that is essential for analyzing attrition trends within the company. 
Each record provides information on an employee's demographics, employment history, job characteristics, 
and compensation, allowing us to explore the factors contributing to attrition.**

## Key Data Attributes

1. **Total Number of Attrition Count:**

**Description: Total count of employees who have left the company within a specified period**.

**Purpose: Helps calculate attrition rate and understand turnover trends.**



2. **Current Employment:**

**Description: Count of employees who are currently active in the company.**

**Purpose: Provides a measure of the existing workforce for comparison with attrition data.**



3. **Employee Count**:

**Description: The number of records in the dataset, which represents the total number of employees (active and departed).**

**Purpose: Establishes the size of the dataset and serves as a baseline for calculating attrition metrics.**



4. **Age Range:**

**Description: The minimum and maximum age of employees in the dataset.**

**Purpose: Helps identify any age-related trends in attrition.**



5. **Attrition Rate:**

**Description: The percentage of employees who have left the company in a given period.**


6. **Total Number of Employees:*8

**Description: The sum of current employees and those who have left the company.**

**Purpose: Helps in calculating attrition rate and analyzing the overall workforce.**



7. **Department:**

**Description: The department where the employee works (e.g., Marketing,Medical,Lab Scientist, HR).**

**Purpose: Assists in identifying attrition trends across departments.**



8. **Job Role:****

**Description: Specific job titles held by employees88 **

9. **Marital Status:**

**Description: The marital status of employees (e.g., Single, Married, Divorced).**

**Purpose: Explores whether marital status has an impact on attrition trends.**

10. **Overtime:**

**Description: Indicates if the employee works overtime (Yes/No).**

**Purpose: Examines if overtime contributes to attrition.**

11.** Educational Qualification:**

**Description: The highest level of education achieved by the employee (e.g., HND, Bachelor’s, Master’s).**

Purpose: Assesses the influence of education level on attrition.

12. **Hourly Rate:**

**Description: The hourly wage rate for each employee.**

**Purpose: Provides insight into compensation and its relation to attrition.**

13. **Monthly Income:**

**Description: The total monthly earnings of each employee**.

**Purpose: Helps analyze how income levels impact attrition.**

14. **Performance Rating:**

**Description: A rating that indicates the employee's performance level (e.g., 1 to 5 scale)**.

**Purpose: Assesses if there is a correlation between performance and attrition.**

15. **Marital Status : Shows the details of staff that are married and not yet married*


#### Additional Notes

**This dataset, with its rich mix of demographic, job-related, and compensation data, is structured to facilitate detailed analysis of the 
factors driving attrition. It enables the development of predictive models to forecast attrition and provides insights to 
support HR strategies aimed at improving employee retention**.


# HR DASHBOARD #

![image](https://github.com/user-attachments/assets/ac717ee6-02d2-41fa-aa50-991ec15a4f82)


**In analyzing the HR data for the Incubator Hub, we can derive insights and recommendations based on the attrition rate 
and other related metrics. Here’s a structured breakdown of the insights and recommendations from the provided data:**

Data Summary

Total Employees: 1,470

Current Employees: 1,233

Total Attrition: 237

Attrition Rate: 16.2%

Average Age of Current Employees: 37 years


Insights

1. Attrition Rate:

**An attrition rate of 16.2% is significant, indicating that over one in six employees leaves the organization within a year.
This is higher than the average turnover rate across industries, which is typically around 10-15%. High attrition can lead 
to increased recruitment and training costs, and it may affect team morale and productivity.**



2. **Current Employee Demographics:**

**The average age of current employees is 37, which may suggest a workforce that is relatively experienced. However, it may also 
imply potential future attrition as older employees approach retirement age. Understanding the distribution of age within the 
workforce can be critical for succession planning.***


3. **Impact on Team Dynamics:**

**With a considerable number of employees leaving, there could be disruptions in team dynamics, knowledge transfer, and project
continuity. High turnover may lead to increased workloads for remaining staff, which can further contribute to attrition.**



4. **Root Causes of Attrition:**

**It is essential to investigate the reasons behind the 237 departures. Factors may include job satisfaction, work-life balance, 
career advancement opportunities, compensation, and workplace culture.**




## RECOMMENDATIONS

1. **Conduct Exit Interviews:**

**Implement a structured exit interview process to gather qualitative data on why employees leave. Analyze this feedback to identify 
common themes or issues.**
**


2. **Enhance Employee Engagement:**
3. 
**Develop programs aimed at improving employee engagement and satisfaction. This may include regular feedback mechanisms, team-building
activities, and recognition programs that celebrate achievements**.



5. Career Development Opportunities:

Offer clear career progression paths and professional development opportunities. Consider mentorship programs or training sessions to help 
employees grow within the company.



4. **Review Compensation and Benefits:**

**Analyze whether compensation and benefits are competitive within the industry. Adjustments in pay or benefits might be necessary to retain 
talent.**



5. **Focus on Work-Life Balance:**

Promote a healthy work-life balance through flexible work arrangements, mental health resources, and wellness programs.



6. **Diversity and Inclusion Initiatives:**

Foster a diverse and inclusive workplace culture to enhance employee satisfaction and retention. This can be achieved through diversity training and initiatives that celebrate varied backgrounds and perspectives.



7. **Regular Employee Surveys:**

Implement regular employee satisfaction surveys to monitor morale and gauge the effectiveness of initiatives aimed at reducing attrition. Use this data to make informed decisions about HR policies and practices.




## CONCLUSION ##

Addressing attrition is crucial for maintaining a stable workforce and ensuring the long-term success of the HR Incubator Hub.
By understanding the underlying reasons for employee departures and implementing targeted strategies to enhance job satisfaction and retention, the organization can reduce attrition rates and build a more committed and productive team.
