## Reward Program Data Analysis  - Data Cleaning Process
**Overview**

This document outlines the steps I followed to clean the dataset used for analyzing mentor-mentee sessions.
The objective was to ensure the dataset was accurate, consistent, and ready for further analysis.

## Data Cleaning Steps
1. **Data Exploration**
   
   I began by exploring the dataset to understand its structure, identify patterns, and detect any potential issues such as missing values, duplicates, and inconsistent formatting.
    The exploration helped to flag areas requiring cleaning for effective analysis.
   
2. **Removing Duplicates**

To remove duplicates, I focused on the following key columns:
- Mentor_ID
- Mentee_Name
- Session_Number
- Session_Date
     
   Using Excel's built-in functionality, I identified and removed records where all four values matched exactly in another record.
   In total, 9 duplicate records were removed, ensuring data integrity without redundancies.

3.**Handling Missing Values**

 I identified essential fields whose absence would negatively affect the analysis:

   - Mentor_ID
   - Mentee_Name
   - Session_Date

Records missing any of these essential fields were removed entirely. Non-essential fields with missing values were retained, as their absence does not impact further analysis. 
Excel's conditional formatting was used to highlight and remove blanks efficiently.

4. **Standardizing the Dataset**

I took the following steps to standardize the dataset:

- Capitalization: All entries in the Mentor_ID and Mentee_Name columns were standardized by capitalizing names uniformly.
- Abbreviations: I checked for abbreviations that might skew further analysis and ensured consistent full names were used.
- Date Format: All dates were converted to the standard format YYYY-MM-DD, ensuring consistency across the dataset.
  
5. **Column Removal**
   
To streamline the dataset, I removed Column A, which contained irrelevant information, focusing on key data points that would directly impact our analysis.

## Conclusion
The dataset has been cleaned and standardized, ensuring it is now ready for effective analysis.
These steps will help improve the accuracy and reliability of insights derived from this data.




