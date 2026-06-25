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
-	Microsoft Power BI
-	Power Query
-	DAX
-	Data Modeling
-	Data Visualization

### KEY SKILLS APPLIED
- Data Gathering, Cleaning and Transformation
 > Data was imported into Power BI then it was transformed by power query where cleaning, exploration and transformation were carried out.
- Data Modelling

<img width="970" height="537" alt="Dano model table" src="https://github.com/user-attachments/assets/5f57d1fd-eb91-43e8-ba56-d05dcc0cca40" />

- New Measures and DAX Expressions 
> Key performance indicators (KPIs) were calculated using New Measures and DAX
- Data Visualization	Slicers were added to allow leadership to filter into specific customer segments when needed.

### VISUALIZATION
KPI (Key Performance Indicator Metrics)
|KPI| VALUES|
|--------------------------|--------|
|Total Passengers| 129,880|
|Average Age|	39 Years|
|Satisfaction Rate|	43.4%|
|Dissatisfaction Rate|	56.6%|
|Returning Passenger Satisfaction Rate|	47.8%|
|First-Time Passenger Satisfaction  Rate|	24.0%|


##### DASHBOARD

<img width="1120" height="542" alt="Dano 2" src="https://github.com/user-attachments/assets/e7fc9f47-f858-48f8-ac46-68da338286be" />



### KEY INSIGHT
1. Satisfaction by Travel Type
> Findings
-	Business travelers show significantly higher satisfaction levels.
-	Personal travelers exhibit higher dissatisfaction levels.
> Implication
Business travelers appear to receive greater value from the airline experience compared to personal travelers.

2. Satisfaction by Class
> Findings
-	Business Class passengers have the highest satisfaction levels.
-	Economy passengers show the highest dissatisfaction levels.
-	Economy Plus performs slightly better than Economy but remains below Business Class.
> Implication
Service quality differences between travel classes strongly influence customer satisfaction.

3. Satisfaction by Check-In Service
> Findings
- Satisfied passengers rated check-in services higher than dissatisfied passengers.
> Implication
- A smooth and efficient check-in process contributes positively to customer experience.

4. Satisfaction by In-Flight Service
> Findings
- Higher in-flight service ratings correspond with increased satisfaction levels.
> Implication
- Service quality during flights plays a critical role in shaping customer perception.

5. Satisfaction by Seat Comfort
> Findings
- Passenger satisfaction increases significantly as seat comfort ratings improve.
- Low seat comfort ratings are associated with higher dissatisfaction.
> Implication
- Seat comfort is a major driver of customer satisfaction.

6. Satisfaction by Baggage Handling
> Findings
- Passengers who rated baggage handling highly were more likely to be satisfied.
- Lower baggage handling ratings are strongly associated with dissatisfaction.
> Implication
- Efficient baggage management directly impacts customer experience.


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


