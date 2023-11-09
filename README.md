# data_512_project  

## Project Goal 
The common research question that to be answered was:
What are the estimated smoke impacts on your assigned city for the last 60 years? 
The goal for this section of the project was to acquire the geospatial data, generate an estimate for smoke impact in the city and develop a model that can forecast the estimate for the next 25 years.


## Data Source
The dataset that has been used for this analysis - https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81
This dataset is designed be to a comprehensive collection of fire boundaries within the United States and provides a more thorough and complete picture of fires across the United States when compared to the datasets that went into it.

## Documentation
In order to generate the AQI for each year for the city of Benicia, we used the US EPA Air Quality System API.
Further the following example notebook was used under the CC-BY license.
Sample Notebook for AQI Generation - https://drive.google.com/file/d/1bxl9qrb_52RocKNGfbZ5znHVqFDMkUzf/view   
Example Notebook for Reading in the Wildfire Data - https://drive.google.com/file/d/1qNI6hji8CvDeBsnLDAhJXvaqf2gcg8UV/view
We also used the GeoJSON reader provided by Professor David McDonald for the above purpose under the same licence. 
Link - https://drive.google.com/file/d/1TwCkvdaw0MxJzW7NSDg6XxYQ0dvaS44I/view
CC-BY License - https://creativecommons.org/licenses/by/4.0/  
 
## Environment
Jupyter was used in order to run a .ipynb Notebook. Any editor that allows .ipynb notebooks can be used to run this project following the installation of the modules specified in the code.

## License
This project is open-source and follows the MIT License. You are free to use and modify the code following the terms of the MIT License.

## Steps to Reproduce:
1)	Install and import the necessary Python libraries.  
2)	Run the Jupyter notebook which contains the code to retrieve the data from the google document and the APIs, preprocess it, upload it into the output files and create the necessary visualizations. 

## Errors Handled
The data for 2021, 2022 and 2023 was missing from the dataset. So, the analysis was restricted to the range of 1963 to 2020. Further, the US EPA Air Quality System API only provided data from 1986 onwards and also contained a few rows of missing data. Therefore, the visualization was created using data that was available from both data sources.

## Intermediate Files 
aqi.json - results of the US EPA Air Quality System API   

