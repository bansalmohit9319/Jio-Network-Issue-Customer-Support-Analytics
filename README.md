# Jio CareOps Network Issue Analyzer

##  About the Project

The **Jio CareOps Network Issue Analyzer** is a data analytics project that I developed to understand customer complaints and identify possible service-related issues.

In a telecom company, customers may face network problems, recharge issues, or delays in resolving their service requests. Analyzing these issues can help the operations team understand what is going wrong and decide which cases need attention first.

Through this project, I worked with customer complaint data and related operational records to clean the data, combine information from different sources, identify potential risks, and generate useful reports.

## Project Objectives

The main objectives of this project are:

- Clean and organize customer complaint data.
- Analyze network-related issues across different sites.
- Identify recharge-related risks and service request follow-ups.
- Understand repeat customer complaints.
- Combine different datasets into one complaint-level master table.
- Assign priority levels to complaints from P0 to P3.
- Generate reports and summaries to support operational decision-making.

##  Tools and Technologies

- **Python** – For data processing and analysis.
- **Pandas** – For data cleaning, transformation, and aggregation.
- **Google Colab** – For writing and executing Python code.
- **CSV and Excel** – For storing and exporting the final reports.

##  Key Features

- Data cleaning and standardization.
- Network issue analysis by site.
- Recharge risk identification.
- Service request and escalation analysis.
- Repeat customer identification.
- Complaint-level master dataset.
- Rule-based risk scoring and prioritization.
- Priority-wise and circle-wise summaries.
- Search and filtering of complaint records.
- CSV and Excel report exports.

##  Complaint Priority Classification

The project assigns priorities based on the operational risk signals identified in the data.

| Priority | Meaning |
| P0 | Highest priority; requires urgent attention |
| P1 | High priority; needs prompt follow-up |
| P2 | Medium priority; requires review |
| P3 | Routine priority; no major risk signal identified |

The priority score is calculated using network issues, recharge risks, service follow-ups, and repeat customer complaints.

These priority levels help organize cases so that potentially serious issues can be reviewed first.

##  Project Workflow

I divided the project into 10 milestones to make the analysis easier to manage.

1. Loaded the customer complaint data.
2. Loaded network, recharge, and service request records.
3. Cleaned complaint data and standardized important fields.
4. Cleaned operational datasets and standardized dates.
5. Analyzed network reports by site.
6. Summarized recharge-related information for each complaint.
7. Analyzed service requests, escalations, and repeat customers.
8. Combined the analyzed data into a master complaint table.
9. Identified operational risk signals and assigned complaint priorities.
10. Generated the final reports, summaries, and export files.
