## Data Analysis Notebooks for COMM2550 Data Project

* This folder contains the series of Jupyter notebooks we created to do our data analysis.


1. `NY_analysis.ipynb` - the notebook containing the loaded data from The New York State Fish Stocking Data in the data folder. The series of cells in the notebook aim to explore, clean, and filter the data to fit our investigative needs. 
    * First the raw data set was filtered for instances where Lake Ontario was stocked. 
    * Then, a year filter was applied to extract only the recorded years which the New York and Ontario datasets had in common (2013 to 2023). 
        * this subset was saved as `NY_lakeontario_2013-2021.csv` in the `data` folder
    * This new data subset was then used to visualize all Lake Ontario stocking occurrences and amount of stocking by species across 2013 to 2023 in New York.
      
2. `Ontario_analysis.ipynb` - the notebook containing the loaded data from The Ontario GeoHub Fish Stocking Data in the data folder. The series of cells in the notebook aim to explore, clean, and filter the data to fit our investigative needs. 
    * First the raw data set was filtered for instances where Lake Ontario was stocked. 
    * Then, a year filter was applied to extract only the recorded years which the New York and Ontario datasets had in common (2013 to 2023).
        * this subset was saved as `ON_lakeonatrio_2013-2021.csv` in the `data` folder
    * This new data subset was then used to visualize all Lake Ontario stocking occurrences and amount of stocking by species across 2013 to 2023 in Ontario.
        
3. `Combined_analysis_and data_questions.ipynb` - the notebook containing the subset of the raw dataframes saved the two analysis notebooks above. Combining our individual analyses into one notebook was essential for the comparing of fish stocking data between the US and Canada.
    * First the subset data from our above notebooks was downloaded, and individual data frames were cleaned further by renaming columns before merging.
    * Then, New York and Ontario subsets were combined into one `combined_df` dataframe.
    * This time, one bar graph contained visualization for both countries. The first looks at Average Stocking of Each Species Per Year, and the second looked at Total Stocking of Each Species Per Year.
    * Finally, A seaborn plot was created to show two line plots side by side. One showing total stocking of each species in the US, and the other showing total stocking of each species in Canada.
