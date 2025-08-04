# task1_data_cleaning
Medical Appointment No Shows Source: Kaggle This dataset contains information about over 110,000 medical appointments in Brazil and whether patients showed up or not.
📊 Summary Report – Task 1: Data Cleaning and Preprocessing
🗂️ Dataset Used:
Medical Appointment No Shows
Source: Kaggle
This dataset contains information about over 110,000 medical appointments in Brazil and whether patients showed up or not.

🧰 Tools Used:
Python

Pandas Library

🧼 Steps Performed During Data Cleaning:
Loaded Dataset using Pandas and explored structure using .info() and .head()

Removed Duplicate Records using .drop_duplicates()

Renamed Columns to lowercase and consistent format (e.g., No-show → no_show, Handcap → handicap)

Converted Date Columns (scheduled_day and appointment_day) to datetime format using pd.to_datetime()

Checked for Missing Values using .isnull().sum() — No missing values were found

Standardized Values in columns like gender to ensure consistency

Fixed Data Types (converted patientid from float to string to avoid scientific notation)

📤 Output:
A cleaned dataset saved as cleaned_medical_appointments.csv

A Jupyter Notebook containing step-by-step code and explanation for all cleaning steps

Ready for further analysis or visualization

