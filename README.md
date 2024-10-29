## Crowdfunding Data Processing and Analysis
This project processes crowdfunding and contact data to extract key information for analysis. Using Python libraries such as Pandas and NumPy, the data is read, transformed, and exported to CSV files.

# Project Overview
The project contains three main parts:
1. Category and Subcategory Extraction: Reads crowdfunding data and extracts unique categories and subcategories.
2. Campaign Data Processing: Transforms the crowdfunding data into a campaign.csv file.
3. Contacts Data Processing: Extracts and structures contact data from a contacts.xlsx file to create a clean contacts.csv.

# Key Components
# 1. Category and Subcategory DataFrames
- Extracts unique categories and subcategories from the crowdfunding.xlsx file.
- Creates and exports two CSV files:
     - category.csv containing unique category_id and category.
     - subcategory.csv containing unique subcategory_id and subcategory.

# 2. Campaign DataFrame
- Reads and processes crowdfunding.xlsx to create the campaign.csv file.
- Columns include contact_id, description, goal, pledged, launch_date, and end_date.
- Merges category and subcategory IDs for better data organization.

# 3. Contacts DataFrame
- Reads contacts.xlsx to create the contacts.csv file with contact_id, first_name, last_name, and email.
- Uses regular expressions and string methods to extract key information from raw data.

# Dependencies
- Pandas: Data manipulation and analysis.
- NumPy: Efficient array operations and numerical calculations.

# Running the Code
- Ensure input data files are available in the Resources folder.
- Execute the code sequentially to:
      - Read, transform, and export category.csv and subcategory.csv.
      - Process and export campaign.csv.
      - Extract and structure contacts data, exporting contacts.csv.
