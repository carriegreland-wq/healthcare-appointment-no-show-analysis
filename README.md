# Healthcare Appointment No-Show Analysis
Exploratory data analysis of medical appointment no-shows using
![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![SQL](https://img.shields.io/badge/SQL-BigQuery-informational)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)
![Healthcare Analytics](https://img.shields.io/badge/Domain-Healthcare%20Analytics-green)

![Dashboard Preview](images/dashboard.png)

<img width="1786" height="847" alt="Healthcare Appointment No-Show Analysis Dashboard" src="https://github.com/user-attachments/assets/e9f57378-2308-480c-b9b3-4368f32f53a1" />



## Project Overview
Missed medical appointments are a significant operational challenge in healthcare systems. No-shows can disrupt provider schedules, reduce clinic efficiency, and delay care for other patients.

This project analyzes patterns in medical appointment attendance to identify factors associated with higher no-show rates. The goal is to uncover insights that healthcare organizations could use to improve scheduling practices and patient outreach strategies.

The analysis was conducted using SQL in Google BigQuery and Python in Google Colab, with results presented in an interactive Tableau dashboard.

## Dataset
**Source:** Kaggle – Medical Appointment No Shows Dataset  
**Records:** ~110,000 medical appointments in Brazil  

Key features include:
- Patient age
- Gender
- Neighborhood
- Scholarship status
- Chronic conditions
- SMS reminder received
- Appointment attendance (show / no-show)

## Project Objectives
- Identify demographic and scheduling factors associated with missed appointments
- Analyze how appointment lead time impacts no-show rates
- Evaluate the impact of SMS reminders on attendance
- Create a dashboard to communicate key insights

## Tools Used

| Tool | Purpose |
|------|---------|
| SQL (Google BigQuery) | Data querying and aggregation |
| Python (Google Colab) | Data analysis |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Tableau Public | Interactive dashboard and data storytelling |

## Tableau Dashboard
An interactive dashboard was created in Tableau to visualize the key patterns discovered during the analysis.

The dashboard highlights:
- How appointment lead time influences no-show rates
- Differences in attendance across age groups
- The relationship between SMS reminders and missed appointments
- Key insights derived from the analysis

**View the interactive dashboard here:**  
https://public.tableau.com/views/HealthcareAppointmentNo-ShowAnalysis_17740416727200/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Key Findings

### 1. Lead Time Strongly Influences No-Shows
Appointments scheduled further in advance tend to have higher no-show rates. As the number of days between scheduling and the appointment date increases, patients are more likely to miss their appointments.

### 2. SMS Reminders Show Higher No-Show Rates
Patients who received SMS reminders showed higher no-show rates than those who did not. This likely reflects that reminders are targeted toward patients already considered at higher risk of missing appointments.

### 3. Younger Patients Miss More Appointments
No-show rates were higher among younger adults compared to older patients. Older patients tend to attend scheduled appointments more consistently.

## Operational Recommendations

### Reduce Long Scheduling Lead Times
Appointments scheduled far in advance were associated with higher no-show rates. Healthcare organizations may reduce missed visits by minimizing long scheduling gaps when possible.

### Target High-Risk Patient Groups
Younger patients showed higher no-show rates. Targeted reminder strategies and engagement efforts could help improve attendance among these groups.

### Evaluate SMS Reminder Strategies
SMS reminders may be targeted toward higher-risk patients. Future analysis could examine whether the timing or content of reminders influences attendance.

## Project Structure
healthcare-appointment-no-show-analysis/
│
├── README.md
├── appointment_noshow_analysis.ipynb
├── data/
│   └── KaggleV2-May-2016.csv

## How to Run the Project

1. Download the dataset from Kaggle  
2. Open `appointment_noshow_analysis.ipynb` in Google Colab or Jupyter Notebook  
3. Upload the dataset file when prompted  
4. Run all cells in order
5. View the interactive Tableau dashboard via the link in the Tableau Dashboard section above

## Future Improvements
- Build a predictive model to identify high-risk no-show appointments
- Explore additional reminder strategies and timing
- Analyze appointment patterns by day of week and time of day
- Expand the dashboard with additional operational metrics

## Author
Carrie Greland  
https://www.linkedin.com/in/carrie-greland-53397b73/
https://github.com/carriegreland-wq/healthcare-appointment-no-show-analysis
