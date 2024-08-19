# Hospital Waitlist PowerBI Dashboard

## Overview
![Overall Dashboard](https://github.com/user-attachments/assets/749b1274-e50b-4cdd-ae87-298c7c7d5f6b)
![detail](https://github.com/user-attachments/assets/6ecc334e-829b-40d4-a581-c9028170b058)

### Project Plan
The primary objective of this project is to analyze hospital waitlist data in order to identify specialties that may require additional personnel and to detect any long-term trends in the waitlists. This analysis is essential for optimizing resource allocation and improving patient care within the hospital system.

### Dataset
The dataset comprises over 500,000 rows of detailed waitlist data from a large hospital chain. The data is divided into two primary categories: inpatient and outpatient data, each spanning over four years.

- **Inpatient Data**: Refers to patients who are admitted to the hospital and require an overnight stay. These cases often involve more severe conditions that need prolonged monitoring and treatment.
- **Outpatient Data**: Refers to patients who receive medical treatment without being admitted to the hospital. These cases typically involve less severe conditions or follow-up treatments that do not necessitate an overnight stay.

To facilitate comprehensive analysis, the inpatient and outpatient datasets were combined into a single table, allowing for an integrated view of all waitlist data across the four-year period. The richness of this dataset enables both longitudinal (long-term) insights and cross-sectional analysis, providing a robust foundation for understanding trends and patterns in hospital waitlists.

### Data Attributes
The key attributes selected for visualization in the dashboard include:

- **Total Waitlist**: This attribute shows the number of patients on the waitlist for each entry, giving a clear picture of the demand for medical services across different specialties. The visualization includes an option to toggle between __average__ and __median__ calculations, allowing for flexible analysis.
  
- **Specialty**: Indicates the hospital department or medical specialty associated with the waitlist entry (e.g., General Surgery, Cardiology). This allows for the identification of departments with the highest waitlist volumes.
  
- **Archive_Date**: The date on which the waitlist data was recorded. This attribute is essential for tracking changes and trends over time.
  
- **Case Type**: Categorizes the type of medical case, which is vital for distinguishing between different levels of patient care requirements:
  - **Day Case**: Refers to cases where patients are admitted for surgery or procedures that do not require an overnight stay. These cases are typically less complex and allow for same-day discharge.
  - **Inpatient**: Refers to cases where patients are admitted to the hospital for one or more nights. These cases generally involve more serious conditions or surgeries that require extended care.
  - **Outpatient**: Refers to cases where patients receive treatment or consultations without being admitted to the hospital. These visits are usually brief and involve less intensive care.
  
- **Time Bands**: This attribute indicates the duration for which the patient is expected to require frequent or continuous care. It helps in forecasting resource needs and planning for patient follow-up care over time.


## Insights

The dashboard allows for interactive analysis, enabling users to toggle between median and average waitlist measures using slicers. This flexibility is crucial for identifying which specialties have the highest waitlist counts and exploring ways to optimize departments to reduce these waitlists.

### Highlighted Findings

To simplify the analysis, a multi-row card was designed to highlight the top 5 specialties by either average or median waitlist, depending on the chosen measure. Here are some key insights:

#### Paediatric Dermatology
Paediatric Dermatology emerged as the specialty with the highest waitlist during the specified timeframe:

![avg_paed_derm](https://github.com/user-attachments/assets/eda583ff-b771-46ad-8265-b0f820ca0915)

- **Key Observations**:
  - The majority of the waitlist consists of day cases.
  - The most common time band is 18+ months, indicating that Paediatric Dermatology cases often require frequent check-ups for over a year.
  - A noticeable uptick in inpatient cases occurred around April 2019.

These insights suggest that the hospital may need to allocate more resources to Paediatric Dermatology to better manage the long wait times and high demand.

#### Cardiology
Cardiology also ranks among the top specialties with a high median waitlist:

![median cardiology](https://github.com/user-attachments/assets/573fe43b-1181-4671-8644-7d84c894b055)

- **Key Observations**:
  - Both inpatient and day case waitlists have remained consistent from 2018 to 2021.
  - Outpatient cases, however, have shown a slight upward trend over the same period.

These trends can help guide resource planning to maintain consistency in service delivery and manage the increasing outpatient demand.

### Detailed Analysis

For a more granular view, the dashboard provides a detailed page where users can drill down further. For instance, if you want to analyze the waitlists specifically for Cardio-Thoracic Surgery within the Cardiology department, focusing only on inpatient cases and senior citizens, you can do so:

![Cardio_Thoracic surgery_65](https://github.com/user-attachments/assets/985d99e4-7848-45d8-b3ca-15984f984453)

This level of detail supports targeted decision-making, ensuring that hospital resources are allocated efficiently to meet the needs of specific patient groups and medical specialties.





