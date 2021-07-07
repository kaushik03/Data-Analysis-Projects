# Covid-19 Data Analysis
---


![Covid_Poster](https://scwcontent.affino.com/AcuCustom/Sitename/DAM/022/data_graph__virus_Adobe.jpg)

## Data List

- [x]  USA County Wise
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
        
-   [x]