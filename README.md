# Hospital-Analysis-and-Report
Report and Analysis only
Hospital Admissions Dashboard — Data Analysis Report
Dataset: 1,000 patient records
Overall 30-day readmission rate: 21.0%
Overall recovery rate: 69.8%
Average treatment cost: 332,278
Average length of stay: 7.46 days

________________________________________
Part 1: Key Findings
1. Which month has the highest readmission rate?
October recorded the highest readmission rate at 26.74%.
Month	Patients	Readmissions	Readmission Rate
October	86	23	26.74%
March	72	14	19.44%
June	99	21	21.21%
November	90	20	22.22%
August	84	12	14.29%
Insight: October's rate was approximately 5.7 percentage points above the overall 21.0% rate. August recorded the lowest rate at 14.29%.
Management implication: October should be examined for changes in patient volume, case mix, discharge practices, staffing, or follow-up processes that may contribute to the increase.
<img width="634" height="345" alt="Power Bi capture" src="https://github.com/user-attachments/assets/5e6364a7-2524-464f-b4b8-9a25a87768e7" />


________________________________________
2. Which department contributes most to readmissions?
Cardiology contributes the most readmissions.
•	137 patients
•	38 readmissions
•	27.74% readmission rate
•	18.10% of all readmissions
Emergency follows with 36 readmissions, while Surgery recorded 25.
Department	Patients	Readmissions	Readmission Rate
Cardiology	137	38	27.74%
Emergency	192	36	18.75%
Surgery	153	25	16.34%
Orthopedics	130	27	20.77%
Pediatrics	120	22	18.33%
Neurology	101	23	21.78%
ICU	85	20	23.53%
Oncology	82	20	24.39%
Insight: Cardiology has both the largest number of readmissions and one of the highest department-level readmission rates, making it a key area for review.
<img width="634" height="344" alt="Power BI 2" src="https://github.com/user-attachments/assets/d349dc2d-39f5-4d4c-b002-f0757333f6d8" />


________________________________________
3. Do shorter hospital stays result in higher readmissions?
The data shows a clear association between very short stays and higher readmission rates, but this should not be interpreted as proof that short stays cause readmissions.
Length of Stay	Patients	Readmissions	Readmission Rate
1–3 days	228	72	31.58%
4–7 days	275	40	14.55%
8–10 days	212	41	19.34%
11–14 days	285	57	20.00%
Patients staying 1–3 days had a 31.58% readmission rate, more than twice the 14.55% rate among patients staying 4–7 days.
Insight: Very short hospital stays are associated with elevated readmission risk. This may indicate that some patients are being discharged before their conditions are sufficiently stabilized or before adequate discharge planning/follow-up is completed.
Recommendation: Review early-discharge cases, particularly patients discharged within 1–3 days, and strengthen discharge planning and post-discharge follow-up.

________________________________________
4. Which age group is most at risk?
The 65–90 age group is clearly the highest-risk group.
Age Group	Patients	Readmissions	Readmission Rate
0–17	200	27	13.50%
18–34	170	20	11.76%
35–49	150	20	13.33%
50–64	175	32	18.29%
65–90	305	111	36.39%
The 65–90 group represents 30.5% of the patients but accounts for 52.9% of all readmissions.
Insight: Older patients require substantially more attention during discharge and after hospitalization.
Recommendation: Implement enhanced follow-up for patients aged 65+, including medication review, follow-up appointments, care coordination, and early post-discharge contact.

________________________________________
5. Are higher treatment costs linked to better patient outcomes?
The data does not show a meaningful relationship between higher treatment costs and better outcomes.
The overall average treatment cost is approximately 332,278, while the recovery rate is 69.8%.
Cost Group	Average Cost	Recovery Rate	Readmission Rate
Lowest 25%	142,977	70.4%	20.0%
25–50%	263,357	68.0%	18.4%
50–75%	378,652	70.4%	23.6%
Highest 25%	536,125	70.4%	22.0%
Despite the highest-cost patients receiving treatment averaging 536,125, their recovery rate was 70.4%, virtually identical to the lowest-cost group at 70.4%.
The statistical association between treatment cost and recovery in this dataset is very weak.
Insight: Higher spending alone does not appear to translate into substantially better patient outcomes.
Management implication: Management should examine value for money, treatment efficiency, resource utilization, and whether high-cost interventions are producing measurable clinical benefits.

________________________________________
6. Which departments are high cost but poor outcome?
Using average treatment cost and non-recovery rate as the main indicators, two departments stand out for management attention:
Cardiology
•	Average treatment cost: 378,818
•	Recovery rate: 66.42%
•	Poor/non-recovered outcome rate: 33.58%
•	Readmission rate: 27.74%
Cardiology has the highest number of readmissions and the highest department readmission rate, while its average treatment cost is above the hospital-wide average.
Oncology
•	Average treatment cost: 526,870
•	Recovery rate: 68.29%
•	Poor/non-recovered outcome rate: 31.71%
•	Readmission rate: 24.39%
Oncology has the second-highest average treatment cost but its recovery rate remains below 70%.
ICU — important cost-monitoring area
ICU has the highest average treatment cost at 627,743, but it should be interpreted differently from Cardiology and Oncology because its recovery rate is actually relatively high at 76.47%.
Therefore, ICU is primarily a high-cost department requiring cost-efficiency monitoring, rather than being classified as a high-cost/poor-outcome department based on this dataset.

________________________________________
Part 2: Management Summary
Executive Summary
The analysis of 1,000 hospital admission records shows an overall 21.0% 30-day readmission rate, with significant differences across months, departments, age groups, length of stay, and treatment costs.
October recorded the highest monthly readmission rate at 26.74%, while August recorded the lowest at 14.29%. This variation suggests that management should investigate operational and clinical factors associated with the October increase.
Cardiology represents the most significant departmental readmission concern, recording 38 readmissions and a 27.74% readmission rate. It also accounts for 18.10% of all readmissions. Oncology and ICU also have relatively high readmission rates of 24.39% and 23.53%, respectively.
Patient age is one of the strongest risk indicators in the dataset. Patients aged 65–90 recorded a 36.39% readmission rate, substantially higher than every other age group. Although this group represents only 30.5% of the patient population, it accounts for approximately 52.9% of all readmissions. This makes older patients a priority group for enhanced discharge and post-discharge care.
Length of stay also shows an important pattern. Patients staying 1–3 days experienced a 31.58% readmission rate, compared with only 14.55% among those staying 4–7 days. This indicates an association between very short stays and readmissions, although the data alone cannot establish that shorter stays directly cause readmissions.
The analysis also finds little evidence that higher treatment costs produce better outcomes. Patients in the highest treatment-cost quartile had an average cost of approximately 536,125 and a 70.4% recovery rate, virtually the same recovery rate as the lowest-cost quartile. Management should therefore focus on treatment effectiveness and value rather than expenditure alone.
Priority Areas for Management
1. Cardiology: Prioritize readmission reduction and review discharge and follow-up procedures.
2. Oncology: Investigate the combination of high treatment costs, 24.39% readmission rate, and 31.71% non-recovery rate.
3. Patients aged 65–90: Establish enhanced post-discharge monitoring and follow-up.
4. Very short stays: Review patients discharged after 1–3 days to identify avoidable early readmissions.
5. High-cost treatment: Evaluate whether expensive interventions are generating measurable improvements in patient outcomes.
Data-Driven Recommendations
1.	Strengthen discharge planning, particularly for patients with stays of 1–3 days.
2.	Introduce enhanced follow-up for patients aged 65+, including early post-discharge contact and medication/care-plan reviews.
3.	Conduct a Cardiology readmission review to identify recurring diagnoses, discharge issues, and preventable readmissions.
4.	Review Oncology treatment pathways to determine whether high expenditure is producing appropriate clinical outcomes.
5.	Monitor cost against outcomes at department level, rather than using treatment expenditure alone as a measure of performance.
6.	Investigate the October readmission spike to determine whether it reflects changes in patient mix, service demand, staffing, or discharge patterns.
7.	Establish a recurring management KPI dashboard covering readmission rate, recovery rate, average treatment cost, average length of stay, and outcomes by department and age group.
Overall Management Conclusion
The strongest areas requiring management attention are Cardiology readmissions, elderly-patient follow-up, very short hospital stays, and the relationship between treatment expenditure and patient outcomes. The data suggests that reducing readmissions should focus not simply on increasing treatment spending or length of stay, but on targeted discharge planning, appropriate follow-up, patient-risk identification, and department-specific quality improvement.
