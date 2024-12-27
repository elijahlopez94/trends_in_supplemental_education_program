![alt text](images/other/banner.png)
# Trends in Supplemental Education Program
Author: Elijah Lopez


## Overview
This analysis outlines actionable strategies to improve lead conversion, customer retention, and program effectiveness for two locations offering supplemental education services. To optimize lead conversion, this business should re-engage open leads and inactive accounts, highlight long-term value, and prioritize enrollment efforts during high-interest periods. Tailored marketing strategies targeting parents of late-elementary school students in key zip codes combined with seasonal promotions during the summer can further enhance lead generation. Referral programs and upselling private sessions to high schoolers present additional opportunities to boost revenue and engagement.

Retention and program effectiveness can be strengthened through active communication with families, clear progress tracking, and incentives for long-term commitments. Monitoring student performance at critical milestones ensures mastery and alignment with family goals, while time-based metrics provide clarity on program expectations and outcomes. By aligning these efforts, this business can foster trust, improve operational efficiency, and deliver meaningful results for both students and families.


## Business Problem
This supplemental education program seeks to improve its ability to convert prospective leads into active enrollments, retain students for longer periods, and deliver measurable outcomes that align with family expectations. Addressing these challenges requires identifying patterns in lead behavior, tailoring marketing efforts to key demographics, and ensuring that program offerings effectively meet the diverse needs of students.


## Methods

In order to maintain confidentiality and protect proprietary details I merged source documents (7 in total) based on Lead ID. 

### Leads
* Merged two sources, each with unique information
* Encrypted zip codes
* Condensed lead sources based on key phrases
* Dropped 'bad leads' (no contact information)

### Accounts
* Merged two sources, each with unique information
* Dropped sensitive customer information but otherwise used raw data.
* No null values

### Student Progress per Assessment Level
* Single source document
* Created map for assessment names to grade level equivalent
    * Used this to calculate relative student performance to grade level
* For nulls in grade_on_post_dt. (15) I imputed median grade for the matching assessment level.
* Dropped 'NF' assessment types due to differences in implementation from traditional assessments (18 entries).


### Other
* Converted dates to date time and calculated elapsed time from creation to today
    * Assigned 3 letter abbreviation in 'month' column which was then grouped and plotted for various visualizations
* Created grade map to convert grade from string to integer
    * Used this to calculate grade a time of lead creation and grade at time of enrollment
* Standardized enrollment data to float format


## Results
For location-specific insights, data visualizations, and recommendations, please refer to:
* [README_1](location_1/README_1.md)
* [README_2](location_2/README_2.md)


## Conclusions
This analysis leads to the following recommendations:
### Leads
* Re-engage with ‘open’ leads to push them further in the pipeline.
* Demonstrate long term value to unconverted leads, incentivizing them to come in for assessments if necessary.
* There are great opportunities to convert leads in high volume months that are currently underperforming.
* Summer interest is low. Tailored marketing can help attract new customers while retention efforts can help to stabilize revenue.
    * Marketing should target parents of late-elementary and early-middle school students.

### Accounts
* Re-engage ‘inactive’ accounts for re-enrollment.
* Create a referral program to simultaneously increase revenue and reputation.
* Tailor program offering to grade range.
* Upsell current customers (especially high schoolers) by offering private sessions at key times of the year.
* Increase retention through active communication and progress reporting.
* Incentivize longer commitments to increase average length of stay.

### Student Progress per Assessment Level
* Highlight capability to work with students of all ability levels to build trust and credibility with new leads. 
* Flag students that are failing to achieve a passing score after their second post-assessment to understand reasons why.
    * Target higher pre-assessment scores so students are more likely to pass post-assessment within two attempts.
* Monitor PK completion, checking for true mastery along the way.
* Use time-based metrics to set expectations for interested families and to advise best program to match their objectives to their child's current perforamnce level. These should also be used to communicate progress toward long-term objectives over the course of their enrollment.
    * Visits per Level: 25-35
    * Time per Level: 4.6-6.0 months


## Next Steps
* Use long term and monthly understanding of lead volume and lead conversion/enrollment data to:
    * Make informed decisions about promotional offerings:
        * Incentives for new families to get started.
        * Discounts for continuous enrollment beyond average.
    * Provide appropriate staff training at critical times of the year:
        * Sales training leading up to months of high lead volume.
        * Retention training leading toward the summer.
    * Create structured and realistic expectations of management staff performance.
        * Enhance staff motivation by offering bonuses for exceptional conversion rates.
* Use demographic information to:
    * Create unique marketing campaigns based on location.
    * Tailor marketing efforts to parents of late-elementary and early-middle school students.
* Use student assesssment/enrollment information to:
    * Make program recommendations based on student profile.
    * Strategize on approaches to extend student enrollment.
    * Monitor enrolled students' progress and:
        * Intervene when they are not meeting goals.
        * Communicate with parents about current standing and confirm/reset expectations for the future.


## Opportunities for Improvement
* Clean duplicates in internal system.
* Consistently collect same lead info.
* Track student grade at all critical times (at lead/account creation and for each assessment).
* Record private sessions as enrollments instead of charge to account.
* Always do a post-assessment before moving to a student to the next level.


## For More Information
See the full analysis for:

### Location 1
* [README](location_1/README_1.md)
* [Jupyter Notebook](location_1/eda_notebook_1.ipynb)
* [Presentation](https://docs.google.com/presentation/d/11vkjpD9M5Q125K4gQ_E3Owk-1sUVbmsAAHMwzh5RV2w/edit?usp=sharing)

### Location 2
* [README](location_2/README_2.md)
* [Jupyter Notebook](location_2/eda_notebook_2.ipynb)
* [Presentation](https://docs.google.com/presentation/d/1t9NfPiAyYHQHApuXEDCzWU24HTkprbp7cs_Q3eUn-yE/edit?usp=sharing)


For additional info, contact the author at:

Elijah Lopez | elijahlopez94@gmail.com