
## **Problem Statement**

**Optimizing Resource Allocation in Hospital Management through Length of Stay Prediction**

In the context of the HealthPlus hospital's inefficient management system and the pressing need for better resource allocation, the primary problem revolves around accurately predicting the length of stay (LOS) for patients upon admission. Inefficient distribution of resources such as beds, ventilators, and staff has led to significant complications, resulting in both financial losses and compromised patient care.

## **Objective**

Develop a predictive model to estimate the length of stay (LOS) for patients admitted to HealthPlus hospital, enabling optimized resource planning and allocation.

## Data Dictionary

* **patientid**: Patient ID
* **Age**: Range of age of the patient
* **gender**: Gender of the patient
* **Type of Admission**: Trauma, emergency or urgent
* **Severity of Illness**: Extreme, moderate, or minor
* **health_condition**s: Any previous health conditions suffered by the patient
* **Visitors with Patient**: The number of patients who accompany the patient
* **Insurance**: Does the patient have health insurance or not?
* **Admission_Deposit**: The deposit paid by the patient during admission
* **Stay (in days)**: The number of days that the patient has stayed in the hospital. This is the **target variable**
* **Available Extra Rooms in Hospital**: The number of rooms available during admission
* **Department**: The department which will be treating the patient
* **Ward_Facility_Code**: The code of the ward facility in which the patient will be admitted
* **doctor_name**: The doctor who will be treating the patient
* **staff_available**: The number of staff who are not occupied at the moment in the ward

## Usage

- Run the main_notebook.ipynb
