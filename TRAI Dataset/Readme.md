# Exploratory Data Analysis on TRAI Dataset

![Image](https://thelivenagpur.com/wp-content/uploads/2020/03/MobileNumberPortability-1170x780.jpg)

The Dataset is collected from TRAI website
TRAI stands for **Telecom Regulatory Authority of India** [Dataset source](https://myspeed.trai.gov.in/download/may21_publish.csv)
<br>

The dataset is uncleaned and did not contain any headers
The data has 256562 rows and 6 columns
The 6 columns describes:
1. Carrier
2. Technology (3G/4G)
3. Type (Upload / Download)
4. Speed (in kbps)
5. dBm (Signal Strength)
6. Area (Region)

Since some cellphones couldn't transmit signal strength data, they were written as "na" (in String)

After cleaning the data and doing some formatting on it, the shape of data becomes 204537,6

One thing to notice is that there's different entries for upload and download respectively, this gives us extra information on the usage of the network and the average users extracted from this gives us precise information on the total network because, it might be crucial to know the uploads done to the network too.

Stack used:

| Tools | Version |
| ----------- | ----------- |
| Python | 3.8 |
| Matplotlib | 3.4 |
| Pandas | 1.3 |