# Medical-Appointment-No-Show-Analysis
Exploratory data analysis of medical appointment no-shows using SQL/ Python

# Medical Appointment No-Show Analysis

## Project Overview
Missed medical appointments create scheduling inefficiencies, reduce clinic 
productivity, and delay care for other patients. This project analyzes patient 
appointment data to identify factors associated with higher no-show rates.

Data was analyzed using SQL in Google BigQuery and Python in Google Colab.

---

## Dataset
- **Source:** [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- **Records:** ~110,000 medical appointments in Brazil
- **Features include:** Patient age, gender, neighborhood, scholarship status, 
  chronic conditions, SMS reminder received, and whether the patient showed up

---

## Objectives
- Identify demographic and scheduling factors associated with higher no-show rates
- Evaluate the effectiveness of SMS reminders on appointment attendance
- Explore geographic variation in no-show behavior
- Generate insights that could inform patient outreach strategies

---

## Tools Used
| Tool | Purpose |
|------|---------|
| SQL (Google BigQuery) | Data querying and aggregation |
| Python (Google Colab) | Data analysis and visualization |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |

---

## Key Findings

### 1. Lead Time Strongly Influences No-Shows
Appointments scheduled further in advance tend to have higher no-show rates. 
As the number of days between scheduling and the appointment date increases, 
patients are more likely to miss their appointments.

### 2. SMS Reminders Do Not Reduce No-Shows
Surprisingly, patients who received SMS reminders had a higher no-show rate 
than those who did not. This likely reflects that reminders are sent to 
higher-risk patients rather than causing missed appointments.

### 3. Younger Patients Miss More Appointments
No-show rates were higher among younger adults compared to older patients. 
Older patients tend to attend scheduled appointments more consistently.

### 4. Neighborhood Differences Exist
Some neighborhoods show significantly higher no-show rates than others, 
suggesting geographic or socioeconomic factors may influence appointment 
attendance.

---

## Project Structure
```
healthcare-appointment-noshow-analysis/
│
├── README.md
├── appointment_noshow_analysis.ipynb   # Main analysis notebook (Google Colab)
└── data/
    └── KaggleV2-May-2016.csv           # Source dataset (download from Kaggle)
```

---

## How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
2. Open `appointment_noshow_analysis.ipynb` in Google Colab or Jupyter Notebook
3. Upload the dataset file when prompted
4. Run all cells in order

---

## Conclusion
The analysis suggests that appointment scheduling practices and patient 
demographics influence attendance patterns. Healthcare providers may reduce 
missed appointments by improving reminder strategies and targeting outreach 
efforts toward high-risk patient groups.

---

## Future Work
- Build a predictive model to flag high-risk no-show appointments
- Analyze whether combining SMS with other reminder types improves attendance
- Explore time-of-day and day-of-week patterns in no-show behavior

---

## Author
**[Your Name]**  
[LinkedIn Profile URL] | [GitHub Profile URL]
