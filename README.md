# **Title Data science project on Transportation** <br> <br>

![Title](https://user-images.githubusercontent.com/62517289/145642733-3b6cf4fc-4420-449f-9de9-a2b076f03823.png) <br> <br>
## > Overview: <br>
<p> Driving in NYC can be daunting for student drivers. My hypothesis is that the number of accidents on the road are directly related to how safe the area/road is. I used collisions data and arrest data from NYC OpenData. I first scrape the data off of the database using the built in fitering functions inside NYC OpenData. Then further filtered my data using Python Pandas and plotting them using Matplotlib. </p> <br> <br> 
### > Data 1: <br>
![CrashTime](https://user-images.githubusercontent.com/62517289/145642762-f1cf899f-be82-402b-9419-bd09e0417010.png)
#### > Technique: 
<p> This data comes from the crashes dataset in OpenData, the source dataset was filtered using the date. All data are from the fiscal year of 2021. This data is later used to extract the time when the crashes took place. Then the time was plotted using Python matplotlib. </p>
<br>
### > Data 2: <br>
![Reasons](https://user-images.githubusercontent.com/62517289/145642755-66662ffa-ec91-4451-9f84-c9450f18f858.png)
#### > Techniques: 
<p> This data comes from the crashes dataset, the source was filtered using the same method as mentioned above in Data 1. All data are again, from the fiscal year of 2021. This data is loaded into a pandas dataframe, then the data is processed and counted for each unique reason of crash. Then the top 5 useful reasons for crash was used. </p>
<br>
### > Data 3: <br>
![Arrests](https://user-images.githubusercontent.com/62517289/145642766-e509e3d8-5e0b-49df-88b1-1836779cfc6a.png)
#### > Techniques:
<p> This data comes from the arrest dataset. The source was filtered using OpenData filtering function, the data are all from the fiscal year of 2021. The data contains many other reasons for arrest that are not associated with driving. The data chosen for the causes of the crashes all contain the keyword "Traffic" in it.</p> 
<br>
##### > citations: <br>
-NYC OPENDATA:
-![Crash data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/)
-[Arrest data](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc/)
