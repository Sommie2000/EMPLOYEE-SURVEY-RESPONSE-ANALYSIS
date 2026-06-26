# EMPLOYEE-SURVEY-RESPONSE-ANALYSIS

### PROJECT OVERVIEW
This project analyzes employee satisfaction survey data to identify key factors influencing employee engagement, satisfaction, and workplace experience. The analysis focuses on employee responses conducted by Pierce County WA and completed voluntarily by government employees across different departments and roles to uncover trends, strengths, and areas requiring improvement.

### OBJECTIVE
The primary objectives of this analysis are:
-	Identify survey questions with the highest agreement and disagreement levels.
-	Analyze satisfaction patterns across departments 
-	Measure overall employee satisfaction.
-	Provide actionable recommendations to improve employee experience and retention.


### TABLE OF CONTENT
* [Project Overview](#project-overview)
* [Objectives](#objectives)
* [Dataset Overview](#dataset-overview)
* [Tools](#tools)
* [Key Skills Applied](#key-skills-applied)
* [Visualization](#visualization)
* [Key Insight](#key-insight)
* [Recommendation](#recommendation)
* [Data Source](#data-source)
* [Conclusion](#conclusion)



### DATASET OVERVIEW

COLUMNS:
- Response ID
- Status
- Department
- Director
- Manager
- Supervisor
- Staff
- Question
- Response
- Response Text


##### DATASET SAMPLE PREVIEW

|Response ID|	Status|	Department|	Director|	Manager|	Supervisor|	Staff| Question| Response| Response Text|
|-----------|-------|-----------|---------|---------|-----------|------|---------|---------|--------------|
|1|	Complete|	Human Resources|	0|	1|	0|	0|	1. I know what is expected of me at work|	4|	Strongly Agree|
|2|	Complete|	Communications Office|	0|	0|	0|	0|	1. I know what is expected of me at work|	4|	Strongly Agree|
|3|	Complete|	Parks and Recreation|	0|	1|	0|	0|	1. I know what is expected of me at work|	0|	Not Applicable|
|4|	Complete|	Human Resources|	0|	1|	0|	0|	1. I know what is expected of me at work|	3|	Agree|
|5|	Complete|	Communications Office|	0|	0|	0|	0|	1. I know what is expected of me at work|	0|	Not Applicable|
|6|	Complete|	Prosecuting Attorney's Office|	0|	0|	0|	0|	1. I know what is expected of me at work|	4|	Strongly Agree|

### TOOLS 
-	Microsoft Excel
-	Power Query
-	Data Visualization

### KEY SKILLS APPLIED
-	Data Cleaning and Transformation
  > I transform the data in power query, then I removed duplicate and empty values and I also replace a question “This year, I have the opportunities to learn & grow” to “This year, I have the opportunities to learn and grow” 
-	Survey Analytics
-	KPI Design
-	Data Storytelling
-	Business Intelligence
-	Excel Visualization


### VISUALIZATION

KPI (Key Performance Indicator Metrics)
1. Total Responses
Measures the total number of survey responses received which is 14,575
2. Positive Responses
Measures the number of respondents who selected:
-	Strongly Agree: 5,229
-	Agree : 5731
Total Positive Responses: 10960
3. Negative Responses
Measures the number of respondents who selected:
-	Disagree: 2160
-	Strongly Disagree : 1061
-	Not Applicable : 394 
Total Negative Responses : 3615

4. Employee Satisfaction Rate (54%)
Measures the percentage of positive responses out of total responses.
Formula used : Positive Responses / Total Responses * 100  = 54%



##### DASHBOARD

<img width="1120" height="542" alt="Dano 2" src="https://github.com/user-attachments/assets/e7fc9f47-f858-48f8-ac46-68da338286be" />



### KEY INSIGHT
1.  Agree and Disagree response by Questions 
- The question respondents agree  with the most is:
> My department is inclusive and demonstrate support of a diverse workforce with total number of 663 
- The question respondents disagree with the most is:
> I  have a best friend at work, with total number of  469 

2. Department Response Trend  Analysis
Top 5 Response Trend by Department 
> Yes, there are noticeable patterns across departments.
The Planning and Public Works Department recorded the highest number of survey responses (48%), indicating the highest level of participation among all departments. This department also showed the highest levels of both positive and negative responses, suggesting that employees have strong opinions about their workplace experiences.
The Sheriff’s Department and Human Services also contributed a significant number of responses and generally displayed more positive responses (Agree and Strongly Agree) than negative responses, indicating relatively higher employee satisfaction.
Across most departments, employees tended to agree with statements related to:
●	Understanding what is expected of them at work.
●	Understanding the organization’s mission and purpose.
●	Having supportive workplace relationships.
However, a recurring trend across departments was dissatisfaction with:
●	Career advancement opportunities.
●	Recognition and rewards.
●	Overall job satisfaction.
This suggests that while employees generally understand their roles and work well with colleagues, there are organization-wide concerns regarding employee development, recognition, and long-term career growth.

Top 5 Departments include:
-	Finance and Performance Management 
-	Human Services 
-	Planning and Public Works ( has the highest across all response types)
-	Prosecuting Attomey’s Office 
-	Sheriff’s Department

3. As an Employer, the steps I  would take to improve employee satisfaction based  on the survey results. I will take the following steps;
 (A) Improve Career Development Opportunities
-	Provide training programs, mentorship, and clear promotion pathways to help employees grow professionally. 
(B) Enhance Employee Recognition
-	Introduce reward and recognition programs to acknowledge employees’ hard work and achievements.
(C ) Review Compensation and Benefits
-	Evaluate salaries and benefits to ensure they are competitive and aligned with employee expectations.
(D) Strengthen Leadership and Communication
-	Train managers to communicate effectively, provide regular feedback, and support employees’ needs.
(E) Increase Employee Engagement
-	Conduct regular surveys, feedback sessions, and team-building activities to ensure employees feel heard and valued.
4.  Top 5 Department  by Response
 Shows top 5 departments with the highest number of survey questions response  that Shows positive, neutral, and negative responses for each department.
The department with highest response is Planning and Public works with 48% 
-	Finance and Performance Management (11%)
-	Human Services (10%)
-	Planning and Public Works (48%)
-	Prosecuting Attomey’s Office ( 12%)
-	Sheriff’s Department ( 19%)

5,  Response Type Distribution
Displays the proportion of:
-	Strongly Agree ( 36%)
-	Agree (39%)
-	Not Applicable (3%)
-	Disagree (15%)
-	Strongly Disagree (7%)
Insight
Approximately 75% of respondents provided positive feedback (Agree or Strongly Agree), indicating generally favorable employee sentiment despite concerns in specific areas.

### RECOMMENDATION
1. Improve Economy Class Experience
> Since Economy passengers exhibit the highest dissatisfaction levels, Dano Airlines should:
- Improve seating comfort.
- Enhance in-flight services.
- Increase customer support responsiveness.
2. Enhance Seat Comfort
- Upgrade seating quality.
- Increase legroom where possible.
- Improve cabin ergonomics.
3. Optimize Baggage Handling
- Reduce lost luggage and baggage delays.
- Improve baggage tracking systems.
- Strengthen baggage handling procedures.
4. Improve Check-In Efficiency
- Expand digital check-in options.
- Reduce waiting times.
- Improve airport support services.
5. Focus on First-Time Passengers
> The satisfaction rate among first-time passengers is significantly lower than returning passengers.
 > Dano Airlines should:
- Provide first time experience programs before departure like welcome mails, travel guides, check in instructions, baggage information
- Improve customer communication by sending flight reminders, boarding instructions and airport navigation tips through emails or sms
- Improve ground staff support, by assigning customer service representatives to assist first-time travelers, elderly passengers and passengers requiring guidance
- Follow Up After Flights; collect feedback from first-time passengers and address recurring complaints quickly. This creates a memorable first-flight experience.
6. Improve personal travelers and improve  family friendly services 
  > Provide:
- Family boarding assistance.
- Easier baggage support.
- Child-friendly services
- Increase value perception offers like promotional fares, loyalty reward and discount for repeated leisure travelers.
- Dedicated family check-in counters
- Provide children travel kit like coloring books, child friendly snack and entertainment options

 
### DATA SOURCE
[Airline data.xlsx](https://github.com/user-attachments/files/29183132/Airline.data.xlsx)




### CONCLUSION
The analysis shows that Dano Airlines currently has a customer satisfaction rate of 43.4% and dissatisfaction rate of 56.6% indicating substantial opportunities for improvement. By focusing attention on dissatisfied passengers, especially the first time passengers, economic class and the personal travel type passengers, there should be strategic improvements in seat comfort, baggage handling, check-in efficiency, digital services  and the overall service experience. These initiatives will significantly improve customer satisfaction, customer retention, and brand loyalty.


