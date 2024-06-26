# Cricket-Data-analytics-project
T20 Cricket data preprocessed using Python (Pandas) and analysed using PowerBI

## Data preprocessing (using Python Pandas)
- Data scraped from ESPN cricketinfo site in the form of json files  
- Following Data preprocessing steps performed using Pandas :
  
    a) data extracted from json file and data frame created  
    b) columns renamed  
    c) data from specific columns transformed ( using apply function)  
    d) uneccesary columns dropped  
    e) mapping of data to the newly added column in the dataframe performed  
    f) preprocessed data exported as csv file  

## Data cleaning (using Power BI)
  - Preprocessed data (available in the form of csv file) imported to Power BI  

    a) removed unnecessary characters or symbols in the column by using extract  
    b) sorted and checked for duplicate rows and removed the duplicate rows  
    c) new column added by implementing condition  
    d) datatype of the columns checked and updated  
    e) columns names checked and updated  
    f) new column added by implementing custom column

## Data modelling in Power BI
  ![image](https://github.com/Banuvathyrr/Cricket-Data-analytics-project/assets/145739539/3d9ed337-1ce1-46db-ab0d-523e70102b76)

## DAX Measures 
    a) Total runs = SUM(fact_bating_summary[runs])  
    b) Total_Innings_batted = COUNT (fact_bating_summary[match_id])

