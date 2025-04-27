## **Retail: Accelerating the Sales of the Modecraft Ecommerce Store**

Modecraft (an anonymized real-world company) is an ecommerce store offering a wide range of household items such as mugs, cabinets, lanterns, etc. They have collected processed over 500,000  orders for a diverse global clientele as a business and have now hired you as a consultant to review their data and provide them with business recommendations.

They want to view metrics from both operations and marketing perspectives and seek guidance on areas performing well. As a consultant tasked with analyzing the data of the online retail store, your role is pivotal in understanding and optimizing the company's revenue generation. You'll be diving deep into the available data to uncover insights that will guide the company's strategic decisions for the upcoming year. 

This Datathon is your opportunity to delve into Modecraft's comprehensive data, uncover valuable insights, and develop innovative data-driven solutions that can propel their business to new heights.

## **Dataset Overview**

**Download the Dataset here:**

https://docs.google.com/spreadsheets/d/14JpdZtBkG8mJtfRjrk01R-sQ1WPGgLJXKzZThHx-Zi8/edit?usp=sharing 

**The dataset provided contains the following columns:**

- InvoiceNo (Unique Invoice ID)

- StockCode (Unique Product ID)

- Description (Product Name)

- Quantity (Total Quantity of Product bought in that invoice)

- InvoiceDate (Date and Time at which invoice was created)

- UnitPrice (Price of One Unit of that Product - in UK Pounds)

- CustomerID (Unique Customer ID)

- Country (Country from which order came)

## **Data Analytics and Data Visualization**

### Seasonality Trends Analysis
  
![image](https://github.com/user-attachments/assets/29d59c79-b785-4180-a066-2e7322955cdf)

    The WORLD WAR 2 GLIDERS ASSTD DESIGNS has a strong seasonality pattern which cycles every 6 months. 
    There appear to be two distinct peaks around April and October.


![image](https://github.com/user-attachments/assets/a489ff59-70fc-46d9-9d23-ec2687e81f81)

    The quantity sold of REGENCY CAKESTAND 3 TIER has a obvious downward trend over the years.


![image](https://github.com/user-attachments/assets/d12beceb-04d0-424d-ba19-3a6e848c1db6)

    - December spike likely driven by holiday season sales (e.g., Christmas shopping).
    - January peak could be clearance sales or bulk buying after holidays.
    - Summer (May–July) tends to have smaller basket sizes, potentially due to fewer shopping holidays or events.
    
![image](https://github.com/user-attachments/assets/1a675c99-76fc-41be-afc9-e726d0bd3ca8)

    - Peak in November highlights the importance of holiday-driven sales.
    - The September to November build-up suggests early holiday shopping behavior or strategic campaigns leading up to year-end.
    - Consistent low points in May and early-year months indicate potential off-seasons.
  
 <img width="802" alt="image" src="https://github.com/user-attachments/assets/1944127b-4ddc-4d21-a176-5a923b17c5b9" />

      Seasonal Revenue Trends by Hemisphere
      We separated countries into Northern Hemisphere and Southern Hemisphere groups to investigate the role of seasons in customer spending.
      
      Northern Hemisphere Countries included:
      United Kingdom, France, Germany, USA, etc.
      
      Southern Hemisphere Countries included:
      Australia, Brazil, South Africa (RSA), etc.
      
      Unspecified countries were dropped to avoid noise in the analysis.
      
      Two separate graphs were generated due to significant scale differences between North and South revenues.
      
      Observations:
      Northern Hemisphere
      Sales peak around September to November, corresponding with major holiday seasons (Halloween, Black Friday, Christmas).
      
      Lowest activity is observed in early months (February–March), likely post-holiday slowdowns.
      
      Southern Hemisphere
      Sales peak around June to August, corresponding to their winter season (mid-year shopping and holidays).
      
      Very low sales during December, indicating that Christmas does not drive as significant sales boosts compared to the Northern Hemisphere.
      
      Seasonality plays a major role in revenue cycles, but its effects are hemisphere-dependent.
      
      Marketing campaigns and inventory strategies must be localized:
      
      Northern Hemisphere should emphasize end-of-year holiday promotions.
      
      Southern Hemisphere should focus on mid-year promotions around June-August.

### **Monthly Analysis Report (December 2010)**

  - **Products that sold the most**

|StockCode|Description|Quantity|
|---------|-----------|--------|
|84077    |WORLD WAR 2 GLIDERS ASSTD DESIGNS|     5195|
|21212    |PACK OF 72 RETROSPOT CAKE CASES|       4106|
|85123A   |WHITE HANGING HEART T-LIGHT HOLDER|    3752|
|22834    |HAND WARMER BABUSHKA DESIGN|           3476|
|22197    |SMALL POPCORN HOLDER|                  2737|

  - **Products that sold the least**

|StockCode|     Description|Quantity|
|---------|-----------|--------|                      
|gift_0001_50|  Dotcomgiftshop Gift Voucher 50.00|    1|
|21196|         ROUND WHITE CONFETTI IN TUBE |         1|
|90142D|        MOP PENDANT SHELL NECKLACE |           1|
|90144|         SILVER DROP EARRINGS WITH FLOWER |     1|
|84816|         DANISH ROSE BEDSIDE CABINET |          1|

  - **Products that generated the most revenue**

|StockCode|  Description| Revenue|  
|---------|-----------|--------|    
|22423|      REGENCY CAKESTAND 3 TIER|              27694.76|
|DOT |       DOTCOM POSTAGE     |                   24671.19|
|85123A  |   WHITE HANGING HEART T-LIGHT HOLDER |   10435.36|
|84029E  |   RED WOOLLY HOTTIE WHITE HEART|       9291.73|
|22086  |    PAPER CHAIN KIT 50'S CHRISTMAS    |     9208.10|

  - **Products that generated the least revenue**

|StockCode | Description  | Revenue|  
|---------|-----------|---------| 
|71215    |  METAL BASE FOR CANDLES       |       0.42|
|79151B  |   SILICON CUBE 25W, BLUE |             0.42|
|79149B  |   SILICON STAR BULB  BLUE |            0.42|
|47422  |    ASSORTED MONKEY SUCTION CUP HOOK |   0.42|
|10123C  |   HEARTS WRAPPING TAPE      |          0.65|

  - **Most popular times for purchase during the week**

|TimeOfDay|Orders|
|---------|--------|
|16:57:00  |  721|
|14:09:00  |  701|
|14:25:00  |  692|
|14:41:00  |  664|
|14:59:00  |  646|

    Most purchases happened in the afternoon.

### **Geographical Analysis**

![image](https://github.com/user-attachments/assets/27d3d301-f0fc-47a0-9433-a8cac495d34e)

    United Kingdom dominates the total sale (85%), with much smaller contributions from other countries.

### **Customer Insights**

- **Holiday-Driven Buying Spikes:**
        - Revenue and basket sizes peak in November, suggesting holiday shopping behavior (likely Christmas or end-of-year gifting).
        - Customers buy more items per receipt during this period, contributing to higher overall basket value.

- **Post-Holiday Drop:**
        - Revenue and average basket sizes drop significantly after the holidays (January-February).
        - Customers likely reduce spending after heavy end-of-year purchases.

- **Mid-Year Stability with Occasional Upticks:**
        - Revenue and basket sizes stabilize mid-year, with moderate increases in some months (likely linked to summer events or school breaks).
        - Certain products (e.g., lunch boxes, home décor) show cyclical demand.

### **Specific Product Analysis**

We chose to analysis WORLD WAR 2 GLIDERS ASSTD DESIGNS because it had the most sale during the years.

- **Total Quantity Sold**: 49756

- **Total Revenue Generated**: 12639.88

- **Quantity Sold by Country**
 
![image](https://github.com/user-attachments/assets/579a17fb-1603-42f2-acf2-40a0958ebc5a)

- **Quantity Sold by Month**

![image](https://github.com/user-attachments/assets/b7feb235-aca5-4de0-a409-0babc7ab18b9)

- **Quantity Sold by Day of Week**

![image](https://github.com/user-attachments/assets/71d2d4e0-00e7-43ff-87f9-faffebe54724)

## **Machine Learning Model**

- **For a specific product (each one has a unique stock code) predict:**

    We chose WORLD WAR 2 GLIDERS ASSTD DESIGNS since it had the most sale and has a strong seasonality pattern. We used the exponancial smoothing model the predict futue sales. As we can see in the plot, the predictions roughly matche the yearly sales pattern of the product.

    The predicted next 3 months sale volumns are 1168 units, 2941 units, and 3330 units, with a total quantity of 7439 units and total revenue of about 2732.32.

![image](https://github.com/user-attachments/assets/67bcf5b5-4092-475e-ae9b-449ee83d1581)

- **For the store as a whole predict:**

    RMSE across folds: 972,702 | 376,376 | 760,381
    
    Average CV RMSE ≈ 703,153, meaning the model’s typical error is around 700K in revenue prediction.
    
    Prediction for Jan–Mar 2012:
    
    Total predicted store revenue: ≈ 3.37 million.
    The model captured general store revenue trends reasonably well. Some fluctuations exist (since retail has seasonality, promotions, holidays), but the model still gives useful ballpark forecasts.
  
- **For a specific country predict:**

  - We chose Channel Islands

    RMSE across folds: 253,118 | 321,810 | 618,233
    
    Average CV RMSE ≈ 397,720, much lower than store-wide because UK is the majority market and more stable.
    
    Prediction for Jan–Mar 2012:
    
    Total predicted Channel Islands revenue: ≈ 3.58 million.
.   Predicting this place alone is even more stable and reliable compared to predicting the global store. It drives overall revenue patterns.
