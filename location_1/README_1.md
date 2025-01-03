![alt text](../images/other/banner.png)
# Trends in Supplemental Education Program
Author: Elijah Lopez


## Data
The data used in this project was proprietary and analyzed with explicit permission from the business owner. It was sourced from multiple internal systems and consolidated into three primary datasets to facilitate comprehensive analysis:
* Leads - There are 1,533 leads from Aug 2011 - Dec. 2024 measured on 7 features. These include information such as when the lead was created, lead source, student information, and whether or not they enrolled.
* Accounts - There are 653 accounts from June 2013 - Dec. 2024 measured on 10 features. These include contract start and end dates as well as enrollment length and type, current status, and student information.
* Student Progress per Assessment Level - Assessment data combines all assessments for each grade level a student worked on where the student had attempted at least one post-assessment. There are 356 assessments matching this criteria from 2000-01-01 to 2024-12-09. Each assessment is measured across 12 features such as pre- and post-assessment dates, level, student grade, number of attempts, and per level metrics such as PKs (assignments) and number visits to the center.


## Results
### Leads
#### Lead Volume
![alt text](../images/location_1/leads/leads_over_time.png)
![alt text](../images/location_1/leads/leads_per_month.png)
* Cyclical pattern, except during COVID where it remained at depressed levels.
* New monthly leads average 16.
* New leads are highest in Sept. & Oct. (middle to end of the first quarter).
* New leads are lowest during June & July (summer).

#### Leads Converted
![alt text](../images/location_1/leads/converted_leads_over_time.png)
![alt text](../images/location_1/leads/converted_leads_per_month.png)
* Cyclical pattern but with post-COVID years averaging lower than pre-COVID years.
* Average monthly leads converted is 5.
* Lead conversion is highest in Sept, and the first three months of the calendar year.
* Lead conversion is lowest in Apr. & July (end of school year & summer respectively).

#### Percent Lead Conversion
![alt text](../images/location_1/leads/percent_lead_conversion_over_time.png)
![alt text](../images/location_1/leads/percent_lead_conversion_per_month.png)
* Cyclical pattern with poorest performance starting in 2023.
* Average monthly conversion is 33%.
* Highest conversion rate is in May & June (families more serious about getting summer help).
* Lowest conversion is in Aug. & Oct. (opportunity zone!)

#### Other
![alt text](../images/location_1/leads/student_grade_at_lead_creation.png)

![alt text](../images/location_1/leads/zip_codes_by_count.png)
![alt text](../images/location_1/leads/zip_codes_by_enrollment.png)
* Leads are most common for elementary-aged students, specifically grades 2-5.
* Leads who enroll in the program are most commonly from zip codes 1, 5, and 6.


### Accounts
#### Enrollments Over Time
![alt text](../images/location_1/accounts/enrollments_over_time.png)
![alt text](../images/location_1/accounts/enrollments_per_month.png)
* Average monthly enrollment is 7, indicating mild success with re-enrollments of same students and/or sibling enrollments.

#### Program Types and Student Grade Levels
![alt text](../images/location_1/accounts/enrollments_by_membership_type.png)
![alt text](../images/location_1/accounts/student_grade_at_enrollment.png)
![alt text](../images/location_1/accounts/enrollment_types_by_grade_range.png)
* The dominant enrollment type is the Flexible option. Broken down by grade range we see:
    * Elementary: 68% enrolled in Flexible option with 22% enrolled in Monthly Sessions.
    * Middle: 54/37 split
    * High: 41/37 with a large increase in demand for private sessions (18)
* Student grade at enrollment shifts slightly upward to grades 4-6.

#### Cancellations
![alt text](../images/location_1/accounts/cancellations_over_time.png)
![alt text](../images/location_1/accounts/cancellations_per_month.png)
* Average monthly cancellations is 6.
    * Highest month is Aug. Possibly explained by families wanting to "see how this year goes" before committing to longer term option. (opportunity zone!)
    * Lowest month is Nov. (heading toward semester 1 finals).

#### Net Enrollments Over Time
![alt text](../images/location_1/accounts/net_monthly_change.png)
* Net change in enrollments shows similar patterns (positive in Sept., negative in Aug.)
    * Average Net change per year is +3.

#### Enrollment Length
![alt text](../images/location_1/accounts/length_of_enrollment.png)
* Enrollment length is 4.6 (median) to 6.2 (mean) months.


### Student Progress per Assessment Level
#### Assessment Progress per Attempt
![alt text](../images/location_1/student_assessments/performance_change_by_attempt.png)
![alt text](../images/location_1/student_assessments/post_assessment_attempts.png)
* Students progress most upon first post-assessment attempt at 27%.
    * Subsequent attempts plateau near 7-8% improvement before declining at the 5th attempt.
* Most students pass to the next level within 1-2 attempts.

#### Per Level Metrics
![alt text](../images/location_1/student_assessments/pks_per_level.png)
![alt text](../images/location_1/student_assessments/visits_per_level.png)
![alt text](../images/location_1/student_assessments/months_per_level.png)
* PKs completed is approximately 15.
* Attendance is 25 sessions.
* Time is 4.6 (median) to 6.0 (mean) months.

#### Relative Performance
![alt text](../images/location_1/student_assessments/relative_performance.png)
* Relative student performance is 1.5 (mean) to 1.0 (median) BELOW grade level.


## Conclusions
This analysis leads to the following recommendations:
### Leads
* Re-engage with ‘open’ leads to push them further in the pipeline.
* Demonstrate long term value to unconverted leads, incentivizing them to come in for assessments if necessary.
* With lead interest highest  at the end of the first quarter, focus on enrollment conversion during that time.
    * Best opportunity is in October since it consistently has the most leads but also the lowest conversion rate.
* With lead interest lowest over the summer:
    * Focus marketing efforts to capture additional lead interest.
    * Focus on retention strategies for enrolled families.
* Ensure marketing strategy is tailored to target demographic:
    * Parents of late-elementary school students (grades 3-5).
    * Residents in zip codes 1, 5, and 6.

### Accounts
* Re-engage ‘inactive’ accounts for re-enrollment.
* Create a referral program to simultaneously increase revenue and reputation.
* Tailor program offering to grade range.
* Upsell current customers (especially high schoolers) by offering private sessions at key times of the year.
* Increase retention through active communication and progress reporting, especially leading up to August.
* Incentivize longer commitments to increase average length of stay.

### Student Progress per Assessment Level
* Highlight capability to work with students of all ability levels to build trust and credibility with new leads. 
* Flag students that are failing to achieve a passing score after their second post-assessment to understand reasons why.
    * Target higher pre-assessment scores so students are more likely to pass post-assessment within two attempts.
* Monitor PK completion, checking for true mastery along the way.
* Use time-based metrics to set expectations for interested families and to advise best program to match their objectives to their child's current perforamnce level. These should also be used to communicate progress toward long-term objectives over the course of their enrollment.
    * Visits per Level: 25-35
    * Time per Level: 4.6-6.0 months


## For More Information
See the full analysis in the [Jupyter Notebook](eda_notebook_1.ipynb) or review this [presentation](https://docs.google.com/presentation/d/11vkjpD9M5Q125K4gQ_E3Owk-1sUVbmsAAHMwzh5RV2w/edit?usp=sharing).

For additional info, contact the author at:

Elijah Lopez | elijahlopez94@gmail.com