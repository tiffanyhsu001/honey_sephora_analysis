# Honey Sephora Analysis
This notebook contains general analysis on Honey's product performance based off coupon codes affiliated with Sephora. 

## Topics Covered & Conclusions

### Feature Engineering
1. Time series variables created (month, day of week)
2. Commission percentage, save cost ratio
  
### Exploratory Analysis
Before any analysis, I discovered that Honey's daily tracking measure (in this dataset) is inaccurate. While it may correctly collect all the code use frequencies overall (or by month), on a daily level, they are randomly being pushed to specific days of the month. It is highly unlikely that the first 3 days of a month will take up 99% of code uses, and immediately drop to near 0 values for the rest of the month. Similar behaviors in October & November further my suspicion. Additionally, historically in the retail world, Black Friday usually sets records online & in foot traffic, but there is no indication of such behavior in the data.

### Business Impact & Reach Analysis
#### Commission change over time, on a monthly level 
Even though the most codes were used in November, October had the highest average commission, meaning that in October, Honey on average made more money off each user's order. Unsurprisingly, November had the highest number of coupon code users, because that is the peak of the holiday shopping period.

#### Seasonality in regards to following the retail cycle
During peak holiday shopping season, November, Honey has more commissioned codes than noncommissioned codes, implying seasonality    during this time of the year. After this month has passed, December shows an heavy decrease in coupon code frequencies as well as a more balanced commissioned to non commissioned proportion. Retailers understand the influx of holiday shoppers, and will make more partnerships to ensure more attractive sales to entice customers during this time of the year.

We see a similar effect in September, where major sales from Labor Day occur. Again, after September passes, there is a huge drop in codes uses in October, as well as a more balanced distribution of commissioned vs non commissioned codes. Coupon code popularity and frequency will fluctuate with the standard retail cycle.

#### Commissioned codes vs. non commissioned codes and their effect on business profits & customer impact
Commissioned codes provide better savings percentages than non commissioned codes. Thus, we can conclude Honey's partnership coupon codes do significantly benefit the customer while also bringing in more profit. For increased success, Honey should try to increase the number commissioned coupon codes.
    
#### Popularity in States
Honey's biggest clientbase is in California.
    
### 4. Product Performance Analysis & Recommendations
To optimize product performance in code run duration, I would recommend Honey focus its efforts on improving code run times for Mac OS systems and focus on improving code run durations for Firefox browsers. Additionally, we proved that commissioned codes not only have faster run times, provide better savings percentages, but also yield more customer spending. Thus, to speed up product run time, I would recommend that Honey filters commissioned coupons first to cut down run time.
