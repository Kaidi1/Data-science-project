# **Data science project on Transportation** <br> <br>
![Title](https://user-images.githubusercontent.com/62517289/145651209-79b0678d-32fc-411d-b5c2-f98a5480eede.png) <br> <br>
## > Overview: <br>
Driving in NYC can be daunting for student drivers. My hypothesis is that the number of accidents on the road are directly related to how safe the area/road is. I used collisions data and arrest data from NYC OpenData. I first scrape the data off of the database using the built in fitering functions inside NYC OpenData. Then further filtered my data using Python Pandas and plotting them using Matplotlib. <br>
## >Background: 
My project is about safety on the road and how we can make the road safer for student drivers by showing the areas where accidents are more likely to happen. I hope that showing the amount of accidents, experienced drivers can help reduce the rates and beginner drivers can avoid those areas to practice their driving. <br>

### > Data 1: <br>
![CrashTime](https://user-images.githubusercontent.com/62517289/145642762-f1cf899f-be82-402b-9419-bd09e0417010.png)
#### > Technique: <br>
This data comes from the crashes dataset in OpenData, the source dataset was filtered using the date. All data are from the fiscal year of 2021. This data is later used to extract the time when the crashes took place. Then the time was plotted using Python matplotlib.
<br>
### > Data 2: <br>
![Reasons](https://user-images.githubusercontent.com/62517289/145642755-66662ffa-ec91-4451-9f84-c9450f18f858.png)
#### > Technique: <br>
This data comes from the crashes dataset, the source was filtered using the same method as mentioned above in Data 1. All data are again, from the fiscal year of 2021. This data is loaded into a pandas dataframe, then the data is processed and counted for each unique reason of crash. Then the top 5 useful reasons for crash was used.
<br>
### > Data 3: <br>
![Arrests](https://user-images.githubusercontent.com/62517289/145642766-e509e3d8-5e0b-49df-88b1-1836779cfc6a.png)
#### > Technique: <br>
This data comes from the arrest dataset. The source was filtered using OpenData filtering function, the data are all from the fiscal year of 2021. The data contains many other reasons for arrest that are not associated with driving. The data chosen for the causes of the crashes all contain the keyword "Traffic" in it. 
<br>
#### >Conclusion: <br>
Based on the data and results above. One can conclude that the best time to practice driving would be early in the morning, or late at night. From 1 AM to 7 AM we have the least number of vehicle crashes in FY 2021. We can also see a downward trend between 8 PM to 11 PM. However, 1 AM to 7 AM are not reasonable times for a student driver to practice driving. Moreover, the most perhaps unsurprising, leading, cause of crashes is driver inattention. The number of crashes due to driver inattention/distraction towers about the rest. In my data 3, it is shown that the number of arrests in Staten Island involving traffic/vehicle violations is significantly lower than those of the other 4 boroughs. The number of arrests due to traffic violations is important because those same traffic violations can be shown to have ties to the increase in the number of crashes. I hereby conclude that if a student driver wishes to further improve or gain confidence in their driving skills, they should make the effort to drive around 8 PM to 11 PM and the location for practice should preferably be in Staten Island. <br>
##### > csv files: <br>
-[crash.csv](https://github.com/Kaidi1/Data-science-project/files/7695726/crash.csv) <br>
-[arrest.csv](https://github.com/Kaidi1/Data-science-project/files/7695727/arrest.csv) <br> 
###### > citations: <br> 
-NYC OPENDATA: <br>
-[Crash data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/) <br>
-[Arrest data](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc/)


