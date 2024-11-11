### HR ATTRITION CLASS PROJECT

##  HUMAN RESOURCES INCUBATOR HUB ATTRITION CLASS PROJECT

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



## EXPECTED OUTCOME

**The report will deliver insights on:**

* **Attrition Drivers: Factors like low job satisfaction, long working hours, poor management, or limited growth opportunities**.

**Employee Segments at Risk: Identifying high-risk groups based on demographics, job roles, or tenure.**

* Attrition Rate Forecast: A projection of future attrition rates if current trends continue.**

* **Recommendations: Strategies for HR to improve employee retention, such as policy changes, enhanced**
**training programs, and better compensation packages.**


## Benefits of Analysis

* **With a clear understanding of attrition patterns, the company can:**

* **Optimize Talent Management: Proactively address factors leading to turnover.**

* **Enhance Employee Engagement: **Develop initiatives that improve job satisfaction and employee loyalty.**

* **Cost Savings: Lower recruitment, hiring, and training costs by retaining more employees.**

* **Strategic Planning: Use attrition forecasts to plan workforce needs and ensure business continuity.**


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

**Description: Specific job titles held by employees**

9. **Marital Status:**

**Description: The marital status of employees (e.g., Single, Married, Divorced).**

**Purpose: Explores whether marital status has an impact on attrition trends.**

10. **Overtime:**

**Description: Indicates if the employee works overtime (Yes/No).**

**Purpose: Examines if overtime contributes to attrition.**

11.**Educational Qualification:**

**Description: The highest level of education achieved by the employee (e.g., HND, Bachelor’s, Master’s).**

**Purpose: Assesses the influence of education level on attrition.**

12. **Hourly Rate:**

**Description: The hourly wage rate for each employee.**

**Purpose: Provides insight into compensation and its relation to attrition.**

13. **Monthly Income:**

**Description: The total monthly earnings of each employee**.

**Purpose: Helps analyze how income levels impact attrition.**

14. **Performance Rating:**

**Description: A rating that indicates the employee's performance level (e.g., 1 to 5 scale)**.

**Purpose: Assesses if there is a correlation between performance and attrition.**

15. **Marital Status : Shows the details of staff that are married and not yet married**


#### Additional Notes

**This dataset, with its rich mix of demographic, job-related, and compensation data, is structured to facilitate detailed analysis of the 
factors driving attrition. It enables the development of predictive models to forecast attrition and provides insights to 
support HR strategies aimed at improving employee retention**.


TOOLS USED

## DAX FUNCTION
**MEASURES AND CALCULATED COLUMNS WERE INTRODUCTED TO ACHIEVED DESIRED GOALS**


1. **CALCULATED COLUMNS**

**Calculated columns are new data columns that you create in a table using DAX expressions. These columns are computed row-by-row for each 
entry in a table, and the results are stored as part of the table’s data**.

**LOGICAL FUNCTION: was used to calcualate Job satisying rating and total attrition counT
E.G IF ATTRITION IS YES=0, ELSE = 1**

2. **MEASURES**

**Measures, on the other hand, are dynamic calculations that are performed on data in the context of the visualizations, such as tables, charts,
and graphs. Measures are recalculated on the fly based on the filters applied in the report**.

* **Atrrition Rate = sum('HR data'[Attrition Count])/sum('HR data'[Employee Count])**

* **Average Age of employee = Average('HR data'[Age])**
 

* **AVERAGE TOTAL EMPLOYEE = Average('HR data'[Age])**

**Measures don’t add physical data to the table like calculated columns do; they produce a single value based on an aggregation 
(like sum, average, or count) or a more complex calculation**.

![image](https://github.com/user-attachments/assets/ad547052-84f3-476c-a3d6-7b3b0ac9862a)

![image](https://github.com/user-attachments/assets/df25fee7-9400-43e1-830e-af0f078f0c30)

## HR DASHBOARD 

### HR GENERAL DASHBOARD

![image](https://github.com/user-attachments/assets/3cd59603-57b8-4733-b7fe-25c40f864a7a)


### HR BY JOB ROLE DASHBOARD

* **IMPACT OF ATTRITION ON JOB ROLE (HEALTHCARE)**
   
![image](https://github.com/user-attachments/assets/1a227559-9b03-46c9-a335-30545e41eacf)



* **IMPACT OF ATTRITION ON JOB ROLE (SALES EXCUTIVE)**
  

![image](https://github.com/user-attachments/assets/6d367425-9063-4980-8dad-6b8a8a7b7040)


* **IMPACT OF ATTRITION ON JOB ROLE (LABORATORY TECHNICIANS)**

![image](https://github.com/user-attachments/assets/3a1b018c-f9f6-4894-8074-96fce9705625)


  
* **IMPACT OF ATTRITION ON JOB ROLE (RESEARCH SCIENTIST)**
  
![image](https://github.com/user-attachments/assets/d1c0ba4a-d698-4975-97a2-d22c8b5c4519)


* **IMPACT OF ATTRITION ON JOB ROLE (RESEARCH DIRECTOR)**

![image](https://github.com/user-attachments/assets/d63e46f7-e08d-473b-8dba-635fc0f1ab3e)


* **IMPACT OF ATTRITION ON JOB ROLE (MANAGER)**
  
![image](https://github.com/user-attachments/assets/bd3fb569-07b3-4321-b826-f28d72c9c099)


* **IMPACT OF ATTRITION ON JOB ROLE (HUMAN RESOURCES)**
  
![image](https://github.com/user-attachments/assets/33274388-b360-4672-96eb-b53956971729)


* **IMPACT OF ATTRITION ON JOB ROLE (MANUFACTURING)**
* 
![image](https://github.com/user-attachments/assets/0e4ea503-6217-45de-81ca-21f6aeea2520)



 * **IMPACT OF ATTRITION ON JOB ROLE (SALES REPRESENTIVES)**
 
  
![image](https://github.com/user-attachments/assets/f9b58791-99bf-4c58-9bcc-fbfa7a91eea9)

  

**In analyzing the HR data for the Incubator Hub, we can derive insights and recommendations based on the attrition rate 
and other related metrics. Here’s a structured breakdown of the insights and recommendations from the provided data:**

## HUMAN RESOURCE DATA ANALYSIS SUMMARY

* **Total Employees: 1,470**

* **Current Employees: 1,233**

* **Total Attrition: 237**

* **Attrition Rate: 16.2%**

* **Average Age of Current Employees: 37 years**


## INSIGHT

1. **ATTRITION RATE**:

**An attrition rate of 16.2% is significant, indicating that over one in six employees leaves the organization within a year.
This is higher than the average turnover rate across industries, which is typically around 10-15%. High attrition can lead 
to increased recruitment and training costs, and it may affect team morale and productivity.**



2. **CURRENT EMPLOYEE DEMOGRAPHICS:**

**The average age of current employees is 37, which may suggest a workforce that is relatively experienced. However, it may also 
imply potential future attrition as older employees approach retirement age. Understanding the distribution of age within the 
workforce can be critical for succession planning.***


3. **IMPACT ON TEAMS DYNAMICS:**

**With a considerable number of employees leaving, there could be disruptions in team dynamics, knowledge transfer, and project
continuity. High turnover may lead to increased workloads for remaining staff, which can further contribute to attrition.**



4. **ROOT CAUSES OF ATTRITION**

**It is essential to investigate the reasons behind the 237 departures. Factors may include job satisfaction, work-life balance, 
career advancement opportunities, compensation, and workplace culture.**


## INSIGHT AND RECOMMENDATIONS BASED ON ATTRTION BY JOB ROLES


* **Attrition rates across job roles vary significantly, pointing to different retention challenges and employee experiences.
   Here’s a breakdown:**

Insights:

1. **HIGH ATTRITION ROLES** 

* **Sales Representatives have the highest attrition rate at 40%. This suggests significant turnover, which could be due to high job demands, 
performance pressure, or lack of support.**

* **Laboratory Technicians follow with a 24% attrition rate, which may indicate job dissatisfaction, career progression issues, or
  skill mismatch challenges**.


2. **MODERATE ATTRITION ROLES**:

* **Sales Executives and Research Scientists have attrition rates of 17% and 16%, respectively. These rates, though lower than the highest
  groups, still indicate some retention issues.**

**The attrition rates here may be tied to competitive pressures, career stagnation, or better opportunities outside the company**.



3.  **LOW ATTRITION ROLES** 

* **Research Directors and Managers have the lowest attrition rates (3% and 5%, respectively). Employees in these roles likely experience
better career satisfaction, stability, or benefits that reduce turnover**.



4. **JOB ROLES WITH AVERAGE  ATTRITION**
     
**Healthcare and Manufacturing roles have an attrition rate of 7%, which is moderate and may be driven by a balance between job stability 
and external job opportunities.**



## IMPACT OF ATTRITION ON EMPLOYEE MONTHLY  SALARY AND MONTHLY RATE

![image](https://github.com/user-attachments/assets/15bb04e9-9571-430d-8b76-629d0a3228f8)

* ** Here are the  analysis and recommendations regarding the monthly income, monthly rate, and 
education field as they relate to HR and other fields;**

1. **INSIGHT ON  MONTHLY INCOME AND MONTHLY RATE BY EDUCATION FIELD**


**Life Sciences and Medical fields command the highest monthly incomes and rates, reflecting their demand and specialized skills needed.**
**Life sciences have an average monthly salary of #3.9M and a monthly rate of #8.8M, followed closely by the medical field**.

**Marketing and Technical fields have significantly lower figures, with monthly incomes of #1.2M and #0.8M, respectively, suggesting they 
may be less prioritized or require less specialization in this context**.

**Human Resources ranks the lowest in both income (#0.2M) and rate (#0.4M), which could imply that HR roles are undervalued,
potentially affecting morale and turnover in HR employees.**


~~ **Recommendation: Since HR has lower pay relative to other fields, companies could evaluate if this aligns with their goals for 
employee engagement and retention, as well as their overall organizational culture. Improving compensation for HR could have 
positive effects, as HR plays a critical role in employee satisfaction and operational support**.

2. **ANALYSIS OF MONTHLY INCOME BY JOB ROLES**

**Sales Executives, Managers, and Directors (Research and Manufacturing) have higher monthly incomes, aligning with their seniority and decision-making roles.**

**Health Representatives and Laboratory Technicians have mid-range incomes, which likely reflects their specialized but non-management roles.**

**Human Resources and Sales Representatives are at the lower end, which might make these roles less attractive. Research Scientists also 
have a relatively low income, despite their specialized knowledge.**


~~ **Recommendation: Re-evaluate HR and Research Scientist roles for potential income adjustments. Despite low income, these roles can be vital to 
company operations. Properly compensating HR could improve hiring processes, organizational culture, and employee satisfaction, while better
compensation for Research Scientists might help in retaining innovative talent**.

3. **IMPACT OF ATTENTION ON THE HR MONTHLY INCOME AND RATE**

**If the goal is to increase attention toward HR’s strategic value, consider adjusting monthly incomes and rates for HR roles. 
HR employees play a central role in managing recruitment, talent retention, employee well-being, and company culture. 
When HR departments are underpaid relative to other fields, it can impact their ability to perform these functions effectively. 
An investment in competitive pay for HR roles could yield improvements in organizational effectiveness and employee satisfaction across all departments.**

~~ **Recommendation: To increase the impact of HR, consider**

* **Benchmarking HR salaries with industry standards to ensure competitiveness**.

* **Enhancing HR involvement in strategic decisions to align with higher-paid roles, which can help justify improved compensation**.

* **Exploring performance-based incentives for HR staff to boost engagement and align HR efforts more closely with company goals**.


**This approach should balance attention across roles, ensuring that HR staff feel equally valued as other employees, potentially 
resulting in a more cohesive organizational structure**.


## RECOMMENDATONS ON ATTRITION BY JOB ROLES 

1. **TARGETED RETENTION BY JOB ROLES**

* **Sales Representatives and Laboratory Technicians need focused retention strategies. Consider conducting exit interviews to understand the main reasons
for turnover. Addressing pay, workload, and career development opportunities could reduce attrition in these groups**.



2. **SUPPORT CAREER PROGRESSION**

* **Roles with higher turnover often face career stagnation. Introducing structured career growth paths for Sales Executives,
Laboratory Technicians, and Research Scientists could improve retention by showing a clear roadmap for advancement.**



3. **EMPLOYEE ENGAGEMENT INITIATIVES**

* **Implement regular engagement and feedback sessions, especially for Sales Representatives and Sales Executives, to understand their pain points. Small adjustments 
based on feedback (like flexible schedules or improved sales incentives) might increase job satisfaction.**



4. **ROLE-SPECIFIC PROGRAMS**

* **Consider tailored retention programs. For example, Laboratory Technicians may benefit from skills development and training, while Sales 
Representatives might need more support through mentorship or a clear incentive structure.**



5. **INCENTIVIZE LONG=TERM COMMITMENT** I

* **Offering long-term incentives like stock options, retention bonuses, or paid development programs could make employees more inclined to stay.
This is especially useful for roles with moderate attrition, like Sales Executives and Research Scientists.**



6. **WORKLOAD MANAGEMENT AND TEAM SUPPORT** 

High-pressure roles such as Sales Representatives and Sales Executives might benefit from improved workload management and team support.
This could include setting realistic targets, introducing team-building activities, and promoting a supportive culture.



7. **EVALUATE AND ADJUST COMPENSATION**

* **Competitive pay adjustments for roles with high attrition (like Sales Representatives and Laboratory Technicians) may prevent talent loss. 
Conducting regular market salary reviews could ensure the company remains competitive.**



* **By addressing the specific needs of each job role, these strategies can help balance the overall attrition rate and promote 
long-term employee satisfaction**.

## INSIGHT BASED ON THE ATTRITION CF AGE BAND BY GENDER

![image](https://github.com/user-attachments/assets/7d5c1958-b506-4ba2-a74d-8d7505b2fa2d)

For analyzing attrition by age and gender, I'll break down some insights and recommendations based on the data provided in the above table;

### INSIGHTS

* . **HIGHER ATTRITION IN THE 25-34 AGE GROUP**

**This group shows the highest attrition for both males and females (43 females and 69 males) amounting to 47% of total attrition. This could indicate a 
trend where employees in this age range are likely seeking new opportunities, either for career advancement, higher compensation, or work-life balance**.

**Individuals in this age range are often early to mid-career, where career progression and growth are essential**.

* **LOWER ATTRITION IN OLDER AGE GROUPS** 

**Attrition decreases significantly after age 35, with the lowest levels seen in employees over 55. This could reflect a greater level of job satisfaction, 
stability, or fewer job market options for older employees**.

**Employees over 55 may be close to retirement, making them less likely to seek new roles and more likely to stay for benefits like retirement plans**.


* **GENDER TRENDS IN ATTRITION**

**Males have a higher attrition rate in every age group, with the largest discrepancy in the 25-34 range. This might indicate a gendered aspect of job 
movement or external factors affecting male employees’ career choices**.

**Females have relatively stable attrition rates across age groups, though they peak in the 25-34 group as well**.






## RECOMMENDATIONS BASED ON THE AGE GROUP ATTRITION 

* ** Targeted Retention Efforts for 25-34 Age Group**:

**Consider creating development programs specifically for employees in this age range, such as mentorship, leadership training, or skills development 
initiatives. These can help meet their growth and career progression needs**.

**Introduce flexible benefits, such as remote work or additional time off, which might appeal to younger employees**.

* **FOCUS ON WORK_LIFE BALANCE INITIATIVES**  

**Work-life balance is often a key factor for attrition among younger employees. Enhancing policies that promote work-life balance, 
such as flexible hours or hybrid work models, could help retain talent, especially females in the 25-34 age group**


* **GENDER-specific insights**
  
**Analyze exit interviews (if available) to uncover specific reasons for male attrition, particularly in the 25-34 age range. 
These insights can help tailor retention strategies, whether it’s compensation adjustments, role clarity, or career advancement**.

**For female employees, consider expanding support systems for balancing personal and professional life, as women in younger age 
groups may face unique challenges related to family or caregiving**.

* **IMPLEMENT ENGAGE SURVEYS**

**Conduct regular employee engagement surveys segmented by age and gender to proactively identify factors leading to attrition. 
This will allow the organization to address issues before they lead to employee exits**.

* **LEVERAGE DATA FOR PREDICTIVE ATTRITION MODELLING**  

**Use historical attrition data and additional factors (e.g., department, years in position) to create a predictive model. 
This can provide early warnings for potential high-risk employees, allowing HR to intervene with targeted retention strategies**.


## JOB SATISFACTION RATING BY JOB ROLES OVERVIEW

![image](https://github.com/user-attachments/assets/67a208cd-99fe-4f73-b098-7d69a1944c14)


![image](https://github.com/user-attachments/assets/65b5ce0d-7e21-4354-b30b-89506e27de80)


![image](https://github.com/user-attachments/assets/d9584ac0-bd32-4857-abbe-de3af50b25eb)





## RECOMMENDATIONS

1. **Conduct Exit Interviews:**

**Implement a structured exit interview process to gather qualitative data on why employees leave. Analyze this feedback to identify 
common themes or issues.**
**


2. **Enhance Employee Engagement:**
 
**Develop programs aimed at improving employee engagement and satisfaction. This may include regular feedback mechanisms, team-building
activities, and recognition programs that celebrate achievements**.



3. Career Development Opportunities:

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




## CONCLUSION 

**Addressing attrition is crucial for maintaining a stable workforce and ensuring the long-term success of the HR Incubator Hub.
By understanding the underlying reasons for employee departures and implementing targeted strategies to enhance job satisfaction and retention, 
the organization can reduce attrition rates and build a more committed and productive team.**
