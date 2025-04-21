# Medical-Appointments-No-shows-Analysis
This project investigates how **diabetes** affects patient behavior in attending medical appointments, using a real-world dataset containing over 110,000 records.

## 🎯Objective
To analyze whether patients with **diabetes** are more or less likely to **miss medical appointments**, and explore potential reasons behind their attendance behavior. The aim is to derive insights that can help improve healthcare service delivery and patient follow-up strategies.

## Dataset Used
-<a href="https://github.com/VidyavaVidyavati/Medical-Appointments-No-shows-Analysis/blob/main/Raw%20data.xlsx">Dataset</a>

## 🧹Data Cleaning Summary

### ✅ Performed Cleaning Tasks:
- Removed invalid or unrealistic age values (e.g., negative ages)
- Converted `ScheduledDay` and `AppointmentDay` to datetime format.
- Renamed columns for consistency.
- Created age groups: `Young`, `Middle-aged`, and `Old`
- Checked and fixed data types.
- Standardized binary indicators: 0 = No, 1 = Yes

## Cleaned Dataset
- <a href="https://github.com/VidyavaVidyavati/Medical-Appointments-No-shows-Analysis/blob/main/Cleaned%20data.xlsx">Cleaned Data</a>

## 📊Diabetes vs. No-Show Analysis

We grouped the data by diabetes status to evaluate the effect of diabetes on appointment attendance:

| Diabetes | Total Appointments | No-shows | No-show Rate |
|----------|--------------------|----------|---------------|
| 0        | 102,583            | 20,889   | 0.204         |
| 1        | 7,943              | 1,430    | 0.180         |


### 🔍 Key Insight
Patients with **diabetes are slightly more likely to attend** their medical appointments than those without.

**Possible reasons:**
- Greater health awareness due to chronic illness
- Increased medical supervision
- More frequent need for routine checkups

## 🧾Conclusion
The analysis reveals a modest but meaningful difference in appointment attendance between diabetic and non-diabetic patients. Diabetic patients appear to be **slightly more compliant**, possibly due to the need for regular monitoring and treatment of their chronic condition.

These findings can help healthcare providers tailor follow-up strategies and improve appointment adherence by understanding patient risk factors.

