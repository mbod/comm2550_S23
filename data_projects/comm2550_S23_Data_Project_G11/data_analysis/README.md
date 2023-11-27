## Data analysis notebooks for COMM2550 Data Project

### Data analysis

* There are 3 notebooks in this main folder, used for the data analysis in our project. Each of these 3 notebooks are for each of our research questions (RQ1 to RQ3).

* The RQ1 notebook details our analysis for the relationships between Google search trends and the number of dengue cases.

* The RQ2 notebook details our analysis for the relationships between measures of weather and the number of dengue cases.

* The RQ3 notebook details our analysis for the relationships between Google search trends and measures of weather.

### Data cleaning

* In this folder is also a sub-folder that contains the notebooks used for our data cleaning. As the data obtained from the various sources are dirty and are not standardized, data cleaning had to be performed to ensure that the data was consistent, prior to our anaylsis. 

* The data cleaning folder is organized such that the filenames of the notebooks correspond to the specific datasets that are cleaned. For example, the dengue.ipynb notebook in the data_cleaning folder works on the dengue data downloaded from data.gov.sg.

* The exception is `data_cleaning/trends_dl.ipynb`, which actually details how the data from Google Trends was downloaded. Note that the `pytrends` Python package is required to run this notebook, but it was not possible to install the required package and dependencies here on Jupyter hub, so this notebook will not run as expected here.