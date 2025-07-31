# Hospital_EmergRoom_Analysis_Dashboard

Hospital ER Dashboard
This repository contains datasets and preliminary reports designed to analyze patient flow, satisfaction, and demographic patterns in a hospital Emergency Room (ER) setting. The primary resource is an Excel workbook, Hospital_ER_Dashboard.xlsx, featuring raw data exports, summary statistics, and pivot tables. This resource is ideal for anyone studying hospital administration, data analytics in healthcare, or patient experience optimization.

Contents
Sheet1: Raw ER patient data (first 1000 rows)

Dashboard: Placeholder for visual summaries (currently empty)

Daily Satisfactory Rating: Placeholder for daily trends in patient satisfaction (currently empty)

Average wait time daily trend: Placeholder for daily trends in patient wait times (currently empty)

Daily ER No. of Patient: Placeholder for daily patient counts (currently empty)

Pivot Report: Key metrics and aggregated statistics

Sheet Details
Sheet1: Hospital Emergency Room Data
This core sheet contains anonymized ER visit logs with the following fields:

Patient Id

Admission Date & Time

Patient Name (pseudo-anonymized)

Gender, Age, Race

Department Referral

Admission Status (Admitted/Not Admitted)

Patient Satisfaction Score (where available)

Wait Time

Age Group

Attend Status (Ontime/Delay)

Note: Some values (such as satisfaction scores) are missing in several rows.

Pivot Report
Provides quick aggregated statistics, including:

Total distinct patients: 488

Admission Rates: Admitted 54.5%, Not Admitted 45.5%

Average Wait Time: ~35.2 minutes

Average Satisfaction Score: ~4.8 (scale not specified)

Breakdowns by Age Group, Gender, Race, Referral Department, Attend Status

Daily trends for patient counts, satisfaction, and wait times (for July data only)

Sample Insights
Most ER visits come without referrals (60%).

Slightly more males than females present in the ER.

Largest age group: 0–9 years.

Most patients are seen with delay rather than on time.

Highest daily patient count: 25 (12-Jul).

Satisfaction scores and wait times show daily fluctuation July 1–31.

Usage
Use Sheet1 for direct data analysis, e.g. in Python (Pandas), R, or Power BI.

Use Pivot Report for quick Excel-based summary analytics and dashboard prototyping.

Dashboard and other trend sheets can be built out for data visualization using the raw and pivoted data.

Potential Analyses
Patient flow optimization: Identify bottlenecks by examining wait time patterns.

Demographic studies: Examine which groups are vulnerable to delays or report lower satisfaction.

Daily performance: Track how operational changes may affect patient experience in real time.

Resource planning: Use volume and wait data for shift or staffing adjustments.

Data Source & Anonymity
All patient data in this sample is de-identified and/or simulated. No real names or identifying details are included.

Contributing
Contributions for dashboard build-out, data visualization (Excel/Power BI/Tableau), or further statistical analysis scripts are welcome!
