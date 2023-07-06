# PowerbI-dashboard-projects
PWC-Switzerland-PowerBI-virtual-case

Task 2 : Call Center Trends
Create a Power BI dashabord for Call Center Manager that reflects all relevent Key Perfromace Indicators (KPIs) and metrics in the dataset.

KPIs: 
- Overall Customer Satisfaction.
- Overall calls answered/abandoned.
- Calls by time.
- Average speed of answer.
- Agent's performance quadrant --> average handle time (talk duration) vs calls answered.

Task 3 - Customer Retention
The telecom Retention Manager has scheduled a meeting with the engagement partner at PwC to cover these points:

- Customers in the telecom industry are hard-earned: we don’t want to lose them.
- The retention department is here to get customers back in case of termination.
- Currently, we get in touch after they have terminated the contract, but this is reactionary: it would be better to know in advance who is at risk.
- We have done customer analysis with Excel: it has always ended in a dead-end.
- We would like to know more about our customers: visualised clearly so that it’s self-explanatory for our management.
  
Task 4 - Diversity and inclusion Dashboard
- Number of men
- Number of women
- Number of leavers
- % employees promoted (FY21)
- % of women promoted
- % of hires men
- % of hires women
- % turnover 
- Average performance rating: men
- Average Performance rating: women


Here are some inputs:

- Customers who left within the last month.
- Services each customer has signed up for: phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
- Customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the categories administrative and technical.
- Demographic info about customers – gender, age range, and if they have partners and dependents.
  
Work Flow:

Step 1 - Upload Data
Step 2 - Cleaning data
Step 3 - Transform data
Step 4 - Load data
Step 5 - Data Visualization
Step 6 - Data Analysis
Step 7 - Insights
Step 8 - Suggestions

Flow of work

Step 1 - Upload Data
The Dataset used for this analysis was presented by PWC_Switzerland and available at their official website page.

Step 2 - Cleaning data
Data transformation was done in Power Query and the dataset was loaded into Microsoft Power BI Desktop for modelling. The Customer Retention dataset is given by a table named:
- Customer retention which has 23 columns and 7043 rows of observation.

Column Name	Description
- CustomerID	Represents the unique number of the customer in the dataset.
- Gender	describes the gender of the customer.
- Senior Citizen describes if the customer is a senior citizen.
- Partner	describes if the customer has a partner.
- Dependents describes if the customer has a dependent.
- Tenure describes how long as a customer.
- Phone Service	describes if the customer has registered a phone service.
- Multiple Lines describes if the customer has registered multiple lines.
- Internet Service describes if the customer has registered for internet service.
- Online Security	describes if the customer has registered for online security.
- Online Backup	describes if the customer has registered for online backup.
- Device Protection	describes if the customer has registered for device protection.
- Tech Support describes if the customer has registered for tech support.
- Streaming TV	describes if the customer has registered to stream tv.
- Streaming Movies describes if the customer has registered to stream movies.
- Contract	describes if the length of the contract of the customer.
- Paperless Billing	describes if the customer has registered for paperless billing.
- Payment Method	describes the payment method of the customer.
- Monthly Charges	Represents the monthly charge incurred by the customer.
- Total Charges	Represents the total charge incurred by the customer.
- Num Admin Tickets	Represents the number of admin tickets opened by the customer.
- Num Tech Tickets Represents the number of tech tickets opened by the customer.
- Churn	describes if the customer is at risk of churn or not.
  
Step 3 - Transform data
Data Cleaning and transformation for the dataset were done in power query as follows: 
- Each of the columns in the table was validated to have the correct data type
- Unnecessary rows were removed

Step 4 - Load Data.
- Loading the clean dataset into Power BI.

Step 5 - Data Visualization
- Demographic Info : Shows the male-female distribution,churn by senior citizen,dependents impact,partner impact effect of internet service provider recommendations and a short insight on the report
- Account Info : shows contrct type payment method tenuraity impact on customer count total charges, average monthly charges etc
- Services : shows customer count by streamingTV,customer count by streamingmovies,churn by phoneservice,online security device protection,Tech support etc
- Email / Insights and suggestion :Insights ans suggestions to the engagement partner explaining findings, and include suggestions as to what needs to be changed 

Step 6 - Insights
As shown by Data Visualization, It can be deduced that:
- Out of 7043 customers, 1869 i.e. overall 26.54% customers churned last month.
- 55% of customers were enrolled for month-to-month contract out of which 26.54% were churned last month which is the highest along with that 11.27% customers were churned with one year contract. Two year contract customer churning ratio was only 2.83% (which states that customers having short tenure are more frequently switching than customers having longer tenure)
- Female churn rate is 49.5% and churn rate is 50.5%. Which don't have very big difference of churning as demography.  16.21% of Senior Citizen were churned.
- Customers who are having partners are churning with 48.30% and dependent were churned with 29.96%. (Need to focused on customers who are having partners).
- 1699 customers churned who were having phone service and 170 customers churned who were not enrolled in phone service.
- We were charging average $67.20 with phone service customers and 42.03 with no phone service customers.
- Tenure and contract play an important role in determining whether the customer will churn. Lower tenure will switch frequently by 99%.
- Customer with Fiber optic internet service will churn more compared to DSL internet service holders.
- Payment methods like electronics chek also make a significant impact on the curning decision.

Step 7 - Suggestions
- Senior citizens ration is 16.20% only. However, they are stable customers so can provide then some discount offer for a long tenure.
- Focus more on the customers who are  enrolled in month-to-month contract and using Fiber optics as a internet service because 54.61%customer are churning in this category.
- By starting special offer or reducing the average monthly charges of phone service customers can help us to retain 26.17% customers.
- Can increase the basic plan from 1 month to 3 or 6 month will be a good decision. this will help customer to be with us for a long tenure.
- Can provide special offer to the customer are having partner and using phone service can retain 48.59% customers.

