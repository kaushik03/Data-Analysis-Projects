# Covid-19 Data Analysis
---


![Covid_Poster](https://scwcontent.affino.com/AcuCustom/Sitename/DAM/022/data_graph__virus_Adobe.jpg)

## Used Pandas-Bokeh library. A high-level api for bokeh backend, plot methods using pandas. [pip](https://pypi.org/project/pandas-bokeh/)

## Data List

- [x]  USA County Wise Data Analysis
    - The Data is daily record from 
    1 January 2020 - 31 July 2020 for all counties
    - It comprises of all the Counties in USA States.
    - The Data includes:
        1. UID - Unique ID for the day
        2. ISO3 - Country codes 
        3. Province_State - Name of the County
        4. Lat & Longitude - Location of the County.
        5. Date
        6. Confirmed Cases
        7. Deaths
        <br>
        The Month is extracted from the date, for further Analysis.
        The Analysis is mainly done on Monthly and Provinces Death and Confirmed Cases using the GeoSpatial Data.

        | Libraries | Purpose     |
        | :------------- | :----------: |
        |  Pandas | For Data Wrangling and ETL process   |
        | Datetime  | Date Time operations |
        | Matplotlib  | For plotting Backend | 
        | Seaborn  | For Plotting Data | 
        | Folium  | For Plotting Geo Spatial Data | 
        | Bokeh  | For Interactive Plot | 
        
-   [x] Covid Analysis Country Based:
        - Data Used - Country_wise_latest Data from [Kaggle](https://kaggle.com)
        - The aim in this data, is to get insights on the Covid Cases and recovered patients for each countries.

        | Libraries | Purpose     |
        | :------------- | :----------: |
        |  Pandas | Data I/O, manipulations   |
        | Datetime  | Date Time operations |
        | Matplotlib  | For plotting Backend | 
        | Pandas-Bokeh  | For Interactive Plot |


## Analysis on Covid Cases in India.

1. Data Used:
    - Covid 19 Indi
    - Covid India Status.

    Main aim here was to create dashboard, to demonstrate different aspects of the data.