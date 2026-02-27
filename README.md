🧹 Fashion Dataset Cleaning with Pandas & Matplotlib

Overview
This project demonstrates a complete data preprocessing pipeline using Python’s pandas and matplotlib libraries. The dataset (FashionDataset.csv) contains raw fashion product records that required cleaning, transformation, and deduplication. The workflow ensures the dataset is consistent, reliable, and ready for analysis or machine learning.

Features
📂 Data Import & Inspection: Loaded CSV, explored structure with .head(), .info(), .shape, and .columns.

🧹 Data Cleaning:

Dropped unnecessary columns (Unnamed: 0)

Fixed typos in column names (Deatils → Details)

Removed duplicates and missing values

Standardized text formatting (BrandName, Details)

Replaced placeholders (Nan → NO DISCOUNT, Nan → NA VALUED)

Filtered invalid entries in Sizes

📊 Visualization:

Bar and pie charts showing duplicate row counts

📑 Export:

Final cleaned dataset saved as Cleaned_Fashion_dataset.xlsx

Tech Stack
Python 3.x

pandas – Data manipulation & cleaning

matplotlib – Visualization

Jupyter Notebook – Interactive environment

Results
A fully cleaned and structured dataset

Visual insights into duplicate records

Exported dataset ready for downstream analysis
