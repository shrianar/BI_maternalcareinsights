# MaternalCare Insights

MaternalCare Insights is a **business intelligence solution** developed to address the rising maternal mortality crisis in the U.S. by integrating metadata from **clinical, wearable, and social data** into a centralized, actionable dashboard.

## Overview
Many healthcare systems face challenges in early identification of pregnancy-related risk factors due to **fragmented data** from EHRs, monitoring devices, and community records. This Power BI solution helps overcome these gaps by providing a **maternal risk stratification dashboard** for proactive intervention.

The system supports:
- Early identification of high-risk pregnancies  
- Improved care coordination across providers  
- Real-time monitoring and alerts  
- Cloud-based scalability with role-based access  

---

### Included Datasets (metadata only, de-identified):
1. **Community_Clinic_Records_Cleaned.xlsx**  
   Cleaned records from community clinics containing maternal health visits and vitals.  

2. **EHR_data_maternal_risk_with_insurance_zip.csv**  
   Patient-level risk data enriched with insurance type and geographic ZIP code distribution.  

3. **Final_Consolidated_Maternal_Health_Dataset.xlsx**  
   Master consolidated dataset combining clinic, EHR, wearable, and SDOH data for BI reporting.  

4. **Remote_Wearable_Data_Timestamps.xlsx**  
   Normalized data from wearable health monitoring devices (heart rate, blood sugar, BP, etc.).  

5. **SDOH_Public_data.csv**  
   Social determinants of health dataset (employment status, insurance access, demographics).  

---

## Key Features
- **Interactive Power BI Dashboards** to visualize:
  - Risk distribution by age, insurance, and employment status  
  - Blood sugar levels by risk group  
  - Geographic hotspots of risk in Chicago ZIP codes  
- **Cloud-based Lakehouse Architecture** (Azure Synapse / Databricks) for scalable data integration  
- **Role-based access** for clinicians, coordinators, and administrators  
- **HIPAA-compliant design** with encryption, access control, and audit logging  

---

## KPIs Measured
1. **Percent of high-risk patients flagged before third trimester**  
2. **Reduction in time between risk identification and follow-up care**  
3. **Rate of missed risk indicators due to siloed data**  
4. **Maternal readmission rate within 30 days of delivery**  
5. **Provider engagement rate with the dashboard**  

---

## Dashboard Preview
<img width="1146" height="645" alt="Screenshot 2025-08-21 at 4 58 30 PM" src="https://github.com/user-attachments/assets/e550af30-2ef9-4739-b049-9630b547f967" />

---

## Technical Stack
- **Power BI** – dashboard visualization  
- **Azure Synapse / Databricks** – data integration (lakehouse architecture)  
- **SQL** – ETL and data preprocessing  
- **Cloud Deployment** – scalable, secure, real-time access  

---

## Project Timeline
Implemented using **Agile methodology** with 2-week sprints across:
- Data integration setup  
- Data modeling & architecture  
- Dashboard development  
- Pilot testing & validation  
- Training & rollout  

---

## Risks & Mitigations
- **Data Privacy** → HIPAA compliance, encryption, access control  
- **Adoption Resistance** → phased rollout, user-centered training  
- **Data Quality Issues** → ETL validation, anomaly alerts  

---

## Impact
This solution enables **early interventions** that can significantly reduce complications and maternal mortality. By flagging risks earlier and streamlining care coordination, hospitals and clinics can deliver **more equitable, timely, and effective maternal care**.

---
