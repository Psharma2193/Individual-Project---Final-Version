# Individual-Project---Final-Version


# Individual Project - Final Version
#### By Prachi Sharma

### Datasets Used

1. Speed Camera Violations

2. Red Light Violations

3. Traffic Crashes Violations

Dataset Reference - 

https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4

https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37

https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

## Data Analysis of Speed Camera Violations & Red Light Camera Violations

#### The Datasets are joined on the basis of Zipcodes, Wards & Date of Respective violations to extract the related violations specific to Time & Venue. 

**The Dashboard is published at the below link- **

https://public.tableau.com/profile/prachisharma#!/vizhome/IndividualProject-SpeedViolationAnalysis-FinalVersion/TopBottomZipCodesRedLightSpeedCamViolations?publish=yes

### Data Insight 1 - How does Zipcodes fare in terms of Speed Camera Violations & Red Light Violations? 

The Top 10  & Bottom 10 Zipcodes with highest and lowest Speed Camera Violations are extracted to identify the red Zone areas in Chicago. The mayor of Chicago would be interested in knowing these areas so as to focus on their regulations to control these violations. 

When we bring Red Light Violations into picture we see that the top nor bottom sum of Red light Violations exactly matches with the sum of Speed camera Violation(which is normal) for a Zipcode. But there are peaks and lows in speed violations complementing the red light violations. This graph does give away breadcrumbs for a possible relation between the two to be explored further.

![Data Insight 1](https://github.com/Psharma2193/Individual-Project---Final-Version/blob/master/DI_1.PNG)

### Data Insight 2 - Does Speed Camera Violations relate to Red Light Violations? 

To analyze on the relationship between the two measures, I used scatter plot to understand how much Speed Camera Violations are affected by Red Light Camera Violations. On plotting a scatter plot, their relationship seems to give a positive correlation. This confirms our previous insight that hinted relation between two.

![Data Insight 2](https://github.com/Psharma2193/Individual-Project---Final-Version/blob/master/DI_2.PNG)

### Data Insight 3 - What can we expect for Speed camera violations and Red light violations going forward? 

This visualization presents the existing trend of violations and forecasted violations in coming years. The combined trend line of actual and forecasted  is calculated as a exponential function. The trend line shows that Speed Camera Violations are expected to continue a decreasing trend over the years whereas the Red light violations will mostly remain consistent (subject to policy changes or increasing cameras etc.).

Interestingly, the graph shows that both violations experience peak during the middle period of the year and drops significantly during the end and start of the year.
This graph also confirms our previous analysis of both Violations being related as whenever the Speed Camera violations peaks up or drops there is a similar trend visible in Red Light violations too during the same period. This same pattern is visible in the forecasted trend. 

This gives a cue to authorities to strengthen regulations during these times.

![Data Insight 3](https://github.com/Psharma2193/Individual-Project---Final-Version/blob/master/DI_3.PNG)

## Data Analysis of Speed Camera Violations & Traffic Crashes

#### The Datasets are joined on the basis of Addresses to extract the related violations and crashes specific to a Venue. 

### Data Insight 4 - Do Speed Violations have any impact on Traffic Crashes?

First, I've tried to explore the dataset. Using the total injuries, I identified top Camera IDs that reported maximum no of crashes. Then I brought the speed violations for these Camera IDs and they seem to have followed the similar peaks. On analyzing deeper the speed violations limit for all these camera Id's was 30.
Looking at the Weekday analysis for violations, it came across that the majority of crash injuries reported in children safe zone on Friday and Saturday whereas Weekdays rank highest for Speed camera Violations. Surprisingly, on Thursday there are hardly any violations or crashes reported in the dataset. On analyzing deeper the speed violations reported for all these  

Crashes are serious case of negligence and them happening in the Childen safe zone is a matter of great concern that should be addressed with required actions from authorities. 


![Data Exploration](https://github.com/Psharma2193/Individual-Project---First-Version/blob/master/DI_4-DEX.PNG)


After taking the dta exploration further, I was interested to look at the trend if that shows any relationship between Traffic crashe and Speed camera violations. We see that Speed Camera Violations fluctuates over time but there are less crashes reported consistently. For the location taken in the dataset, the relation between the two measures can not be derived from this graph and require further analysis.

![Data Insight 4](https://github.com/Psharma2193/Individual-Project---Final-Version/blob/master/DI_4.PNG)

### Conclusion

Chicago is widely known for its high crime rate. Handling speed & traffic violations can become secondary for authorities. After looking at the data the authorities can identify the areas that need strict law enforcement like regular police patrolling and ticketing policy. The dataset is from 2014 - 2019 and it clearly speaks that installation of Speed camera in 2014 has led to decline in violation cases over the years. The citizen may have become conscious of their actions as they are at higher risk of getting caught by authorities. This is in a way encouraging and positive signal for authorities to increase cameras in children safety zone to furthermore decrease violations.
