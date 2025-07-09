# Residential Property Price Trends in Lviv 2022-2025

## Project Background and Overview
The residential real estate market in Lviv is one of the most dynamic segments of Western Ukraine's economy. With increasing urban migration, evolving housing preferences, and ongoing infrastructure development, it is essential to understand how different factors affect the final sale price. The goal of the analysis is to expose potential clients to the market and to support informed decision-making for real estate investors, developers, and urban planners.

![image](https://github.com/user-attachments/assets/fd0b3292-506a-44b3-82cc-ccd80726315e)

## Objectives
1. Determine how and what factors affect the final sale price.
2. Provide actionable insights for investment prioritization across districts and apartment types based on discovered factors and trends.

## Data Description
This dataset contains detailed residential property information.
* **_address_**: Address of located apartment (street name and number).
* **_bedroom area_**: Total area of all bedrooms in the property in square meters.
* **_district_**: District of property location.
* **_floor_**: The floor number on which apartment is located.
* **_kitchen area_**: Total area of kitchen in square meters.
* **_material_**: Construction material of the building.
* **_price_**: Listed total sale price.
*** _published_**: The date the listing was published online.
* **_renovated_**: Binary indication of whether the apartment has been renovated (Yes or No).
* **_rooms_**: Total number of bedrooms. 
* **_total area_**: The overall area of the property in square meters.
* **_year_**: Year the building was built. 
* **_average price per square meter_**: Average price per square meter.
* **_total listings_**: Total number of records(listings).
![image](https://github.com/user-attachments/assets/e4250b80-008f-42a4-86ed-38ff257b2a67)

## Executive Summary
Our analysis shows that the average apartment price (including renovated and not renovated) is approximately **$113,000** with a price per square meter of **$1,700/m²**. There were two big price spikes around **March 2023** and **November 2023**. The trend suggests that prices tend to increase after winter, **peaking in the summer** months, and then **decline as winter approaches**. By looking at listing distribution, we can tell that **Sykhiv and Lychakivskiy** districts have **more than 50%** of all listings on the market. However, these two districts show the **highest average price** in the renovated segment for all three categories (1bd., 2bd., 3bd.). For non-renovated properties, prices for Sykhiv district apartments hold low positions, while Lychakivskiy is still showing one of the highest averages in all three categories. Factors such as the apartment floor **do not affect** the price except for floors **12-15**, where we see a price bump; however, the price stabilizes after floor 15. Generally, there is no clear effect of floor on property price, except, as we said, floor 12-15.


## Key Insights and Conclusion
1. ### **Factors affecting the price.**
   One of the most impactful factors for prices is the district in which the apartment is listed. The price difference starts from **$17,000** with the lowest average price of **$62,000** in **Frankivskiy** to **more than $40,000** and average apartment price of **$168,000** in **Lychakivskiy** for non-renovated apartments. Similarly, for renovated apartments, the bottom line for the price difference is around **$20,000** with the lowest average apartment price of $74,000 in **Frankivskiy** district, and the highest difference around **$43,000** and **$184,000** average apartment price in **Shevchenkivskiy** district.

   Another impactful factor for price is renovation status. Non-renovated apartments hold lower prices for a clear reason in most cases; however, the price difference sometimes hits the point where it is worth buying a non-renovated and spending less for renovation. Let's review all cases:
     1. In Frankivskiy district, the price differences start **from $6,000 and up to $24,000**. In this case, it would be better to look for a **renovated apartment**, as the final price for it would be lower.
     2. In Halytskyi district, the difference starts from **$9,000 to $30,000**. In this district, it is definitely worth of finding a renovated 3bd. apartment as the price difference is the lowest ($9,000). For 1bd. apartment, where the price difference is about $15,000, you have more freedom of choosing between non and renovated, as renovation price can be from $15,000 to around $25,000. However, for 2bd., the difference is about $30,000, which makes it worth considering the non-renovated option, as the final price with renovation will be lower.
     3. Lychakivskiy, the most expensive district, differs between **$16,000 and $27,000**. For 1bd. apartment, there is about $17,000 difference, which makes it not crucial to stick to one option. For 2bd., it's better to consider already renovated, as it is only about $10,000 more expensive. However, for 3bd. apartments, it is best to stick to the already renovated option, as in fact, Lychakivskiy have more than $25,000 difference in price in favor of Not Renovated ($168,000) vs. Renovated ($141,000).
     4. For Shevchenkivskiy district, the price difference goes from **$18,000 to $32,000**, and in all cases, it is better to choose the non-renovated option, as the price difference is significant.
     5. Sykhiv district: price difference starts from **$6,000** for 3bd. and rises up to **$33,000** for 1 and 2bd. apartments. It's worth looking for non-renovated in the 1bd and 2bd segment; however, 3bd and renovated look like a better option.
     6. Finally, Zaliznychnyi is very similar to Lychakivskiy; the prices differ from **$1,000 to $16,000**. 1bd and 2bd have about $15,000 price difference, however, not been renovated 3bd. Apartments are about $1,000 more expensive compared to those already renovated.

    Another factor that could play a role in the final price is the monthly trend. The trend suggests that prices tend to increase after winter, **peaking in the summer** months, and then **decline as winter approaches**. There were two anomalies in 2023, the first one occurring around March and the second one around the end of November. During those periods, there was a noticeable price spike.

    Floor number as a factor in the final price is not crucial, and would not make a significant difference in price. However, if the main goal is to save as much money as possible, apartments on floors 12-15 should be excluded from the list, as there is a price bump on this range. Also, for 3 bedroom apartments, there is a price decrease from floor 9 and to floor 11, making it a good option to look at when searching for 3bedroom apartments. All of the other floors do not have any anomalies.
   
2. ### **Insights for Investment Prioritization.**
 
Real Estate market in Lviv, Ukraine, continues to demonstrate **resilient value retention**, positioning it as one of the strongest and **most stable** property markets in the country. Despite high average prices relative to other Ukrainian cities, the diversity in location, renovation condition, and apartment layout offers investors several actionable opportunities for maximizing the return on investment (ROI). 

District-level disparities are substantial and consistent, suggesting that **location** is one of the most influential determinants of price: **Frankivskiy** remains the most affordable district with average prices starting at **$62,000** for non-renovated units. On the high end, **Lychakivskiy and Shevchenkivskiy** are about **20 to 50 thousand** more expensive, showing premium positioning. These differences imply strong district-level price segmentation, allowing investors to tailor their strategies: either enter low-cost markets for flip potential or invest in prime districts for long-term capital appreciation. 

#### Renovation status offers tactical flexibility. 
Renovation condition presents ROI opportunities if navigated strategically: 

  In **Shevchenkivskiy and Sykhiv**, non-renovated apartments often come at a more favorable total cost than buying renovated units. Considering an average of **$20,000 for renovating**, those two districts have good deals for an individual approach to renovations, which could significantly increase the final price for renting or selling opportunities. On the middle of two ends, for **Halytskyi, Lychakivskiy, and Zaliznychnyi** districts potential investors could look at **both option categories** in 1 bedroom and 2 bedrooms options: renovated, and not renovated, as the price difference in those is around **$15-$17 thousand**, which is less than suggested renovation value, however in some cases it is not as significant. Interestingly, in **Lychakivskiy**, 3-bedroom non-renovated apartments are **more expensive** than their renovated counterparts, suggesting anomalies or undervalued renovated listings. **Frankivskiy** is the only district for one and two-bedroom apartments with a relatively low price difference, which should catch investors' eye for purchasing an already **renovated** apartment at a lower cost, opening more investment opportunities. 
 
#### Seasonal timing influences entry points.
Since price patterns reflect a seasonal cycle: **rising after winter**, **peaking in summer**, and **tapering off toward winter**, investors may benefit from entering the market in **late winter or autumn**, just before seasonal upswings. This will save investors from stepping into unexpected anomalies, like those that happened during March and December 2023. 

In conclusion, investors should focus on district-level arbitrage, target non-renovated units in key areas, and leverage seasonal timing for transactions. Lviv's market continues to reward data-driven, location-sensitive investment strategies. 


**Note**: _To check the report with specific cases for investments, please refer to the .ipynb notebook._ (to be added soon...)





