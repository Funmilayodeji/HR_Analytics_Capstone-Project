 *HR_Analytics_Capstone_IOTBTECH PROJECT*

 * Key Insights: Department, Employment Status, Performance, Year of Service, Eligible Bonus.
 
 The Full name field was standardized using Flash Fill, while Dept code and Employment Status were cleaned with Upper and Proper TRIM functions. 
 The Department column was populated using VLOOKUP, and Hiring Date was reformatted with Text to Columns. 
 Any empty salary spaces were filled using the Average Salary, and Performance Band along with Eligibility Bonus were calculated using IF functions to apply     logic based on performance.
 Finally, Years of Service was derived using the ROUND function to calculate tenure from the hiring date.
 
*Insights*

1.  *Attrition Risk in IT & Operations*  
    Analysis shows Left statuses in *Information Technology* and *Operations* which ranges 25%.
    Early leavers also have low Year of Service 2-4 years. This suggests mid-level talent loss.

<img width="393" height="189" alt="image" src="https://github.com/user-attachments/assets/861899e5-44d2-4693-8ea2-ba83744bf271" />


2.  *Performance Gap*  
    A lot of employees are tagged Developing and Needs Improvement. Only a few are Achieving or Exceeding. 
    Departments like Marketing and IT have the most Needs Improvement.
<img width="293" height="149" alt="image" src="https://github.com/user-attachments/assets/8557b9a4-5495-40ff-bf7c-9d205649155e" />

3.  *Performance Distribution*  
    Performance scores range from 38 to 75. A mix of low, mid, and high performers exists across all departments. Departments like Sales and Marketing show         both high and low scores, indicating performance inconsistency.

    <img width="332" height="223" alt="image" src="https://github.com/user-attachments/assets/cffb0997-76b3-4464-9db8-e1adcbc10b5c" />

 4.  *Tenure vs Performance Disconnect*  
    Some employees with 8-11 years of service are still Developing. That means we may have a career growth / upskilling gap.

6.  *Bonus Eligibility Not Tied to Performance*  
    Eligible Bonus is *0.02* to *0.08* across all performance levels. Some Needs Improvement staff are still eligible. This dilutes the incentive.


* Recommendations for Leadership / People& Culture*

*A. Retention*

*Recommendation*: Launch a "Stay Interview + Career Pathing" program for IT and Operations.
*Why*: 60% of leavers in the visible data are from IT/Ops and have 2-6 years tenure. That’s your highest flight risk group.
*Action*: Managers do 1:1s at 2-year and 5-year marks to discuss growth.
<img width="293" height="103" alt="image" src="https://github.com/user-attachments/assets/3e535585-322d-4982-bb65-646d92cbc2c2" />

*B. Performance Management*

*Recommendation*: Tie Eligible Bonus % directly to Performance Rating.
*Why*: Right now Needs Improvement = 0.02 and Exceeding = 0.08. The gap is too small to drive behavior.
*Action*: Change to: Needs Improvement = 0%, Developing = 2%, Achieving = 5%, Exceeding = 10%. This creates clear differentiation.
*Recommendation*: Benchmark salaries by department, tenure, and performance.  
Why: Ensure pay equity and that high performers are competitively compensated.

*C. Learning & Development*

*Recommendation*: Upskilling bootcamps for Developing employees with 5+ years tenure.
 *Why*: You have long-tenure staff stuck at "Developing". That’s a cost + morale risk.
*Action*: Partner L&D with department heads to create 90-day skill plans.

*D. Department Health*

*Recommendation*: Do a pulse survey in Marketing and IT.
 *Why*: These 2 departments have the highest concentration of "Needs Improvement". Could be manager, workload, or training issue.

*E. Workforce Planning*

*Recommendation*: Use Hire Date and Employment Status to forecast hiring needs and build talent pipelines.  
 Why: Proactive planning reduces disruption from attrition.

*Summary for Leadership*

*Insight*: We are losing mid-career IT/Ops talent and have too many long-tenure employees rated "Developing".
*Impact*: Higher hiring cost, lower productivity, weak performance culture.

*Insight*: Attrition is occurring in key departments and performance levels vary widely across the organization.  
Impact: Risk to operational continuity, productivity, and employee morale if not addressed.  
*Recommendation*: 
1.  Targeted retention in IT, Ops, and Finance
2.  Performance differentiation through PIPs and rewards
3.  Salary and workforce planning aligned to tenure + performance
4.  Differentiate bonuses by performance
5.  Career pathing for 2-5 year employees in IT/Ops
6.  Targeted upskilling for "Developing" 5+ year staff
   
<img width="679" height="453" alt="image" src="https://github.com/user-attachments/assets/71506584-3663-467b-86cb-1f9f4fff30ce" />




