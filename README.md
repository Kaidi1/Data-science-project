# **Data science project on Transportation** <br> <br>
![Title](https://user-images.githubusercontent.com/62517289/145651209-79b0678d-32fc-411d-b5c2-f98a5480eede.png) <br> <br>
## > Overview: <br>
Driving in NYC can be daunting for student drivers. My hypothesis is that the number of accidents on the road are directly related to how safe the area/road is. I used collisions data and arrest data from NYC OpenData. I first scrape the data off of the database using the built in fitering functions inside NYC OpenData. Then further filtered my data using Python Pandas and plotting them using Matplotlib. <br>
## >Background: 
My project is about safety on the road and how we can make the road safer for student drivers by showing the accidents that occur. I hope that showing the amount of accidents can push people to be more concerned about the need for safer roads for those who are still learning how to drive. <br>

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
My hypothesis was correct in the fact that the number of accidents on the road are directly related to how safe the road is. Since the numbers were relatively high, this suggests that we need to work on creating a safer space on the road for newcomers and for the safety of the general public. <br>
##### > csv files: <br>
-[crash.csv](https://github.com/Kaidi1/Data-science-project/files/7695726/crash.csv) <br>
-[arrest.csv](https://github.com/Kaidi1/Data-science-project/files/7695727/arrest.csv) <br> 
###### > citations: <br> 
-NYC OPENDATA: <br>
-[Crash data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/) <br>
-[Arrest data](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc/)


