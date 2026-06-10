


<img width="1677" height="938" alt="mocksession_analysis" src="https://github.com/user-attachments/assets/edd6df3b-d236-4c24-90f1-5f2c7aefd68b" />
<img width="1693" height="929" alt="Session_sentimentmock_analysis" src="https://github.com/user-attachments/assets/03744ce3-8000-4904-b2ac-22a5ef25e739" />



# Data Confidentiality Notice
This Portfolio version uses anonymized and representative data. The original project was developed using proprietary company data. While business-sensitive information has been modified, the dashboard architecture, data modeling approach, refresh mechanism, and analytical methodology remain representative of the original solution.

# NGO-Analysis_Deepa
This project analyzes structured teacher feedback data collected from a STEM-focused training program.  The objective was to transform raw multi-sheet feedback data into a structured analytical model and build an interactive Power BI dashboard to support data-driven evaluation and performance monitoring.

Objectives

Evaluate overall training effectiveness

Measure satisfaction levels across schools

Identify strengths and improvement areas

Provide structured reporting for stakeholders

Enable drill-down analysis by zone/school

| Tool              | Purpose                                            |
| ----------------- | -------------------------------------------------- |
| **Power BI**      | Data modeling, DAX measures, dashboard development |
| **Power Query**   | Data cleaning, transformation, merging             |
| **Excel**         | Raw data consolidation                             |
| **Data Modeling** | Relational joins using unique TeacherID            |

-----------------------------------------------------------------------------
DATA WORKFLOW
1️⃣ Data Preparation

Consolidated multiple Excel feedback sheets into a unified dataset

Standardized teacher names and school postings

Cleaned inconsistent text fields (trim, casing normalization)

Created and mapped a unique TeacherID using the master dataset

Resolved duplicate records and formatting inconsistencies
----------------------------------------------------------------------------
2️⃣ Data Modeling

Designed a relational model between:

FactFeedback

Master Teacher Table

Implemented Left Outer Join to preserve all feedback records

Ensured referential integrity using composite matching:

Teacher Name + School

Structured the model for scalability and future integration
-------------------------------------------------------------------------------
3️⃣ Dashboard Development

Built a multi-page interactive Power BI dashboard featuring:

Overall satisfaction KPIs

Rating distribution analysis (Excellent / Good / Fair / Poor)

School-wise performance comparison

Attendance analysis

Qualitative feedback theme insights

Drill-through capability for detailed evaluation
-----------------------------------------------------------------------------------
📌 Key Insights

Majority of participants rated sessions as Excellent or Good, indicating strong overall satisfaction.

Qualitative feedback frequently referenced improved understanding of STEM teaching methodologies.

Teachers reported practical classroom applicability of learned concepts.

Very limited negative feedback suggests consistent training quality.

Minor recommendations included requests for additional hands-on activities and extended session duration.
----------------------------------------------------------------------------------------------------------
Sentiment Analysis (NLP)

Applied VADER (NLTK) sentiment analysis on open-ended qualitative feedback responses
Classified responses into Positive / Negative / Neutral sentiment categories
Visualised sentiment distribution and trends in Power BI using custom DAX measures
Enabled stakeholders to quantify qualitative feedback at scale — across schools, zones, designations, sessions, and training dates
----------------------------------------------------------------------------------------------------------

🎯 Business Impact

Enabled data-driven evaluation of STEM training effectiveness.

Provided structured reporting for NGO stakeholders.

Improved transparency and decision-making visibility.

Created a scalable framework for future training impact assessments.
-------------------------------------------------------------------------------------------------------------
📄 Report Output

Interactive Power BI dashboard

Export-ready PDF reporting format

Executive-level summary insights
------------------------------------------------------------------------------------------------------------
🔐 Data Confidentiality Notice

The dataset used in this project was provided by an external organization for analytical purposes.

Due to confidentiality and data ownership considerations, the original .pbix file and raw datasets are not publicly shared.

The project structure, methodology, data modeling approach, and dashboard design are available for discussion.

For access to a demonstration version or further details, please get in touch with me directly.
