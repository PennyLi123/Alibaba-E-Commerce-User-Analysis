# Alibaba E-Commerce User Behaviour Analysis

# Project Overview

This project utilises `𝐌𝐲𝐒𝐐𝐋` and `𝐓𝐚𝐛𝐥𝐞𝐚𝐮` for the practical process of analysing user behaviour data from the large e-commerce platform 𝐀𝐥𝐢𝐛𝐚𝐛𝐚-𝐓𝐚𝐨𝐛𝐚𝐨. It covers in-depth analysis of 𝐮𝐬𝐞𝐫 𝐛𝐞𝐡𝐚𝐯𝐢𝐨𝐮𝐫, 𝐩𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞 𝐝𝐚𝐭𝐚, and 𝐩𝐫𝐨𝐝𝐮𝐜𝐭 𝐝𝐚𝐭𝐚. Through the exploration of 𝐭𝐫𝐚𝐟𝐟𝐢𝐜 𝐦𝐞𝐭𝐫𝐢𝐜𝐬, 𝐫𝐞𝐭𝐞𝐧𝐭𝐢𝐨𝐧 𝐫𝐚𝐭𝐞, 𝐛𝐨𝐮𝐧𝐜𝐞 𝐫𝐚𝐭𝐞, 𝐮𝐬𝐞𝐫 𝐛𝐞𝐡𝐚𝐯𝐢𝐨𝐫 𝐭𝐫𝐞𝐧𝐝𝐬, and 𝐩𝐫𝐨𝐝𝐮𝐜𝐭 𝐩𝐨𝐩𝐮𝐥𝐚𝐫𝐢𝐭𝐲 𝐫𝐚𝐧𝐤𝐢𝐧𝐠𝐬, it reveals 𝐢𝐧𝐬𝐢𝐠𝐡𝐭𝐬 𝐢𝐧𝐭𝐨 𝐮𝐬𝐞𝐫 𝐬𝐡𝐨𝐩𝐩𝐢𝐧𝐠 𝐡𝐚𝐛𝐢𝐭𝐬 𝐚𝐧𝐝 𝐰𝐞𝐛𝐬𝐢𝐭𝐞 performance 𝐬𝐭𝐫𝐚𝐭𝐞𝐠𝐢𝐞𝐬.

# Project Background and Objectives

(1) Project Background

𝐀𝐥𝐢𝐛𝐚𝐛𝐚 𝐓𝐚𝐨𝐛𝐚𝐨,one of 𝐂𝐡𝐢𝐧𝐚’𝐬 𝐥𝐚𝐫𝐠𝐞𝐬𝐭 𝐞-𝐜𝐨𝐦𝐦𝐞𝐫𝐜𝐞 𝐩𝐥𝐚𝐭𝐟𝐨𝐫𝐦𝐬 founded by Alibaba Group in 2003. With nearly 500 million users and 60 million daily visitors, it hosts over 800 million listings and sees 48,000 transactions per minute.

This project utilises the 𝐓𝐚𝐨𝐛𝐚𝐨 𝐔𝐬𝐞𝐫 𝐁𝐞𝐡𝐚𝐯𝐢𝐨𝐮𝐫 𝐃𝐚𝐭𝐚𝐬𝐞𝐭 provided by Alibaba. The dataset contains all recorded actions (including 𝐏𝐚𝐠𝐞 𝐕𝐢𝐞𝐰𝐬, 𝐩𝐮𝐫𝐜𝐡𝐚𝐬𝐞𝐬, 𝐚𝐝𝐝-𝐭𝐨-𝐜𝐚𝐫𝐭 𝐚𝐜𝐭𝐢𝐨𝐧𝐬, and 𝐟𝐚𝐯𝐨𝐮𝐫𝐢𝐭𝐞𝐬) of approximately 𝐨𝐧𝐞 𝐦𝐢𝐥𝐥𝐢𝐨𝐧 randomly selected 𝐚𝐜𝐭𝐢𝐯𝐞 𝐮𝐬𝐞𝐫𝐬 between 25/11/2017 and 3/12/2017. 


(2) Project Objectives

The goal of this analysis is to explore 𝐮𝐬𝐞𝐫 𝐛𝐞𝐡𝐚𝐯𝐢𝐨𝐮𝐫 𝐩𝐚𝐭𝐡𝐬 and 𝐬𝐡𝐨𝐩𝐩𝐢𝐧𝐠 𝐡𝐚𝐛𝐢𝐭𝐬 on Taobao, optimise 𝐢𝐦𝐩𝐥𝐢𝐜𝐢𝐭 𝐟𝐞𝐞𝐝𝐛𝐚𝐜𝐤 𝐫𝐞𝐜𝐨𝐦𝐦𝐞𝐧𝐝𝐚𝐭𝐢𝐨𝐧𝐬, and help 𝐢𝐦𝐩𝐫𝐨𝐯𝐞 𝐰𝐞𝐛𝐬𝐢𝐭𝐞 𝐬𝐚𝐥𝐞𝐬, fulfill user needs, and 𝐢𝐧𝐜𝐫𝐞𝐚𝐬𝐞 𝐜𝐨𝐧𝐯𝐞𝐫𝐬𝐢𝐨𝐧 𝐫𝐚𝐭𝐞𝐬. Additionally, this project serves as an opportunity to enhance data analysis skills.



# Analytical Framework
The analysis is conducted from 3 dimensions: 
* 𝐖𝐞𝐛𝐬𝐢𝐭𝐞 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞 (how many users visited)
* 𝐔𝐬𝐞𝐫𝐬 (who the users are and what they did)
* 𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐬 (user preferences for products).
Recommendations are provided based on these dimensions. See the diagram below for details.

![Analysis Framework](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Analysis%20Framework.png)



# Advanced SQL Techniques 
* Window Functions (RANK, PARTITION BY)
* Subqueries (Intermediate calculations)
* Views (Reusable complex queries)
* Conditional Aggregation (COUNT(IF...))
* Retention Rate Analysis (DATEDIFF)
* Bounce Rate Calculation (HAVING COUNT)
* RFM Model for Customer Segmentation
* Joins & Data Enrichment (LEFT JOIN, INNER JOIN)



## Alibaba Taobao User Behaviour Tableau Dashboard

### Feel Free to use the interactive [dashboard.](https://public.tableau.com/app/profile/penny.li5621/viz/AlibabaE-commerceUserBehaviourAnalysis/Dashboard1)

![Alibaba User Dashboard.png](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/Alibaba%20User%20Dashboard.png)


# Data Loading and Cleaning

## 1.Data Souce & Description

Dataset File Name: UserBehaviour.csv

Description: Contains all user behaviour data
Included fields: User ID, Product ID, Category ID, Behaviour Type, Timestamp

Behaviour Type:
* pv: product detail page view, equivalent to a click
* fav: add a product to favourites
* cart: add a product to the cart
* buy: product purchase

Dataset Size Details：

| **Dimension**               | **Quantity**    |
|-----------------------------|-----------------|
| Number of Users             | 987,994         |
| Number of Products          | 4,162,024       |
| Number of Categories        | 9,439           |
| Total Number of Actions    | 100,150,807 (100M) |

## 2. Data Import 

* Create a new database named “TaobaoUserBehaviours” using MySQL
  ![data import 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/data%20import%201.png)


* Create a table that matches the structure of the CSV data

    ![data import 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/data%20import%202.png)

* Import External Data Source into table created

  ![data import 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/data%20import%203.png)

  ![data import 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/data%20import%204.png)

  ![data import 5](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/data%20import%205.png)


## 3. Data Cleaning

* Remove Null Values
    ![Remove Null data](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/delete%20Null%20data.png)
  
* Check for Duplicate Values
SELECT user_id, product_id, timestamps FROM userbehaviour
GROUP BY user_id, product_id, timestamps
HAVING count(*)>1;
  ![Duplicate values exist](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Duplicate%20values%20exist.png)
  
* Remove duplicates
Add an ID column and set it as an auto-increment primary key, disable safe update mode, and use self-join to remove duplicate values.
•	Use JOIN to connect the main table with the subquery results (t2) to identify and delete duplicate records with non-minimum IDs, thereby removing duplicates and retaining only one record (min id) per group.
(sql)
ALTER TABLE userbehaviour ADD id INT FIRST;

![Remove duplicates 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Remove%20duplicates%201.png)

![Remove duplicates 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Remove%20duplicates%202.png)

![Remove duplicates 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Remove%20duplicates%203.png)

![Remove duplicates 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Remove%20duplicates%204.png)

  * Add new columns
For easier analysis later, adding three new columns—dates, times, and hours.

![Add new columns 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Add%20new%20columns%201.png)

(sql)
UPDATE userbehaviour 
SET datetimes= FROM_UNIXTIME(timestamps);
•Convert the values in the timestamps column to a standard date and time format, and store them in the newly added datetimes column, where the new column only stores dates and times with no fractional seconds.
•However, the execution took too long (nearly 2 hours) and resulted in an ERROR. Therefore, it was decided to update the data in batches based on the 'id' column, processing 10,000 rows per batch until all records are updated.

 ![Add new columns 2_Error](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Add%20new%20columns%202_Error.png)

 Batch processing：

 ![Batch processing 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%20processing%201.png)
 
The maximum value of the ID is 100,150,807. 
Below are the SQL queries for updating in 10 batches.


 ![Batch 1 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%201%20updated%20.png)
 
 ![Batch 2 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%202%20updated%20.png)

 ![Batch 3 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%203%20updated.png)

 ![Batch 4 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%204%20updated%20.png)

 ![Batch 5 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%205%20updated%20.png)

 ![Batch 6 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%206%20updated%20.png)

 ![Batch 7 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%207%20updated%20.png)

 ![Batch 8 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%208%20updated%20.png)

 ![Batch 9 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%209%20updated%20.png)

 ![Batch 10 updated](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch%2010%20updated%20.png)

 ![Batch1 to 10 verify](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Batch1%20to%2010%20verify.png)

* Extract dates, times, hours components and store in new separate columns
•Create new columns for date, time, hours

 ![Create new columns for date  time hours](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Create%20new%20columns%20for%20date%20%20time%20hours.png)

•Update dates, times, hours columns in bathces

 ![dates times hours batch 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%201.png)

 ![dates times hours batch 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%202.png)

 ![dates times hours batch 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%203.png)

 ![dates times hours batch 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%204.png)

 ![dates times hours batch 5](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%205.png)

 ![dates times hours batch 6](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%206.png)

 ![dates times hours batch 7](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%207.png)

 ![dates times hours batch 8](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%208.png)

 ![dates times hours batch 9](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%209.png)

 ![dates times hours batch 10](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/dates%20times%20hours%20batch%2010.png)

* Check for null values in the newly added columns
318 rows of null data were found

   ![318 row null data](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/318%20row%20null%20data%20.png)

  delete Null data
  
     ![delete Null data](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/delete%20Null%20data.png)

* Remove outlier data
According to the dataset description, the datetimes should be between 2017-11-25 and 2017-12-03. By checking the minimum and maximum values in the datetimes column, records were found that fall outside this range. Therefore, values that do not meet the definition were deleted.

       ![remove outlier 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/remove%20outlier%201.png)

       ![remove outlier 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/remove%20outlier%202.png)
  
# Data Analysis

## (1)	 Website Performance Data 

(a) Traffic data metrics:
•	PV (page view)
•	UV (total unique visitors)
•	Page Depth = PV/ UV


![traffic 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/traffic%201.png)

![traffic 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/traffic%202.png)

![traffic 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/traffic%203.png)

![traffic 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/traffic%204.png)

According to the traffic data metrics table above, 2017-12-02 was a Saturday, and 2017-12-3 was a Sunday. It is evident that the website had higher traffic on the weekend.

(b)	Retention rate
It specifically refers to the average proportion of active users on a given day during a statistical period (week/month) who continue to open the app on day N.
Since the statistical period is relatively short, so only calculates the next-day retention rate.

![retention 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/retention%201.png)

![retention 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/retention%202.png)

(c)Bounce rate
Bounce rate refers to the percentage of visits in which a user enters through a specific landing page and leaves without navigating to any other pages, relative to the total visits to that page.

The number of bounced visitors is 92

![bounce visitor 92](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/bounce%20visitor%2092.png)

Total unique visitors is 6899210.

  ![unique visitors](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/unique%20visitors.png)

Bounce rate=Bounced visitors/Total unique visitors
                               =92/6899210
                               = 0.00133%

## (2) User data 

### (𝐚) 𝐁𝐞𝐡𝐚𝐯𝐢𝐨𝐮𝐫 & 𝐓𝐢𝐦𝐞 𝐂𝐨𝐫𝐫𝐞𝐥𝐚𝐭𝐢𝐨𝐧 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬
Analyse whether users' behaviour is related to time and whether they browse or shop more frequently during specific time periods

  ![behaviour time 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20time%201.png)

  ![behaviour time 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20time%202.png)

  ![behaviour time 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20time%203.png)

### (𝐛) 𝐔𝐬𝐞𝐫 𝐂𝐨𝐧𝐯𝐞𝐫𝐬𝐢𝐨𝐧 𝐑𝐚𝐭𝐞 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 
Counted the number of users for each behaviour type (pv,cart,fav,buy) .
There is 670370 users who ‘buy’.
𝐔𝐬𝐞𝐫 𝐂𝐨𝐧𝐯𝐞𝐫𝐬𝐢𝐨𝐧 𝐑𝐚𝐭𝐞= 𝐧𝐮𝐦𝐛𝐞𝐫 𝐨𝐟 𝐮𝐬𝐞𝐫𝐬 𝐨𝐟 ‘𝐛𝐮𝐲’ / 𝐒𝐔𝐌(𝐔𝐕)
                = 670370/6899210
                =9.72%


 ![conversion 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/conversion%201.png)

 ![conversion 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/conversion%202.png)

 ![conversion 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/%20conversion%203.png)

 𝐂𝐨𝐮𝐧𝐭 𝐨𝐟 𝐝𝐢𝐟𝐟𝐞𝐫𝐞𝐧𝐭 𝐛𝐞𝐡𝐚𝐯𝐢𝐨𝐮𝐫 𝐭𝐲𝐩𝐞𝐬 :
Created a table behaviour_count to store the count of different behaviour types and then inserting the count into that table. 

    ![conversion 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/%20conversion%204.png)
 
 The results are 1998944 ‘buy’ actions, 2852536 ‘fav’ actions, and 5466117 ‘cart’ actions. 

    ![conversion 5](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/conversion%205.png)

𝑷𝒖𝒓𝒄𝒉𝒂𝒔𝒆 𝑹𝒂𝒕𝒆 𝒊𝒔 𝒕𝒚𝒑𝒊𝒄𝒂𝒍𝒍𝒚 𝒄𝒂𝒍𝒄𝒖𝒍𝒂𝒕𝒆𝒅 𝒂𝒔:

𝑩𝒚 𝑼𝒏𝒊𝒒𝒖𝒆 𝑽𝒊𝒔𝒊𝒕𝒐𝒓𝒔 (𝑼𝑽)
Purchase Rate=count of buy actions/sum(UV)
                       =1998944 / 6899210= 𝟐𝟖.𝟗𝟕%
-	This measures the percentage of unique visitors who make a purchase.
-	It tells 𝒉𝒐𝒘 𝒆𝒇𝒇𝒆𝒄𝒕𝒊𝒗𝒆 𝒕𝒉𝒆 𝒔𝒊𝒕𝒆 𝒊𝒔 𝒂𝒕 𝒄𝒐𝒏𝒗𝒆𝒓𝒕𝒊𝒏𝒈 𝒗𝒊𝒔𝒊𝒕𝒐𝒓𝒔 𝒊𝒏𝒕𝒐 𝒃𝒖𝒚𝒆𝒓𝒔.

𝑩𝒚 𝑷𝒂𝒈𝒆 𝑽𝒊𝒆𝒘𝒔 (𝑷𝑽)
Purchase Rate=count of buy actions/sum(PV)
                       =1998944 / 98914480= 𝟐.𝟎𝟐%

-	This measures the percentage of total page views that result in a purchase.
-	It helps analyse 𝒉𝒐𝒘 𝒐𝒇𝒕𝒆𝒏 𝒑𝒖𝒓𝒄𝒉𝒂𝒔𝒆𝒔 𝒉𝒂𝒑𝒑𝒆𝒏 𝒓𝒆𝒍𝒂𝒕𝒊𝒗𝒆 𝒕𝒐 𝒃𝒓𝒐𝒘𝒔𝒊𝒏𝒈 𝒂𝒄𝒕𝒊𝒗𝒊𝒕𝒚.

 𝒇𝒂𝒗 𝒂𝒏𝒅 𝒄𝒂𝒓𝒕 𝑹𝒂𝒕𝒆 = (𝒄𝒐𝒖𝒏𝒕 𝒐𝒇 𝒇𝒂𝒗+ 𝒄𝒐𝒖𝒏𝒕 𝒐𝒇 𝒄𝒂𝒓𝒕) / 𝒔𝒖𝒎(𝒑𝒗)
                                     =（2852536+5466117）/ 98914480= 8.4%
-	Measures the proportion of total page views that resulted in a favourite or add-to-cart action.


### (𝐜) 𝐁𝐞𝐡𝐚𝐯𝐢𝐨𝐮𝐫 𝐏𝐚𝐭𝐡 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 
user behaviour types: pv,fav, cart, buy.
Analyse the user behaviour path to see 𝒘𝒉𝒆𝒕𝒉𝒆𝒓 𝒖𝒔𝒆𝒓𝒔 𝒈𝒐 𝒕𝒉𝒓𝒐𝒖𝒈𝒉 𝒕𝒉𝒆 𝒔𝒕𝒆𝒑𝒔 𝒐𝒇 𝒇𝒂𝒗 𝒂𝒏𝒅 𝒄𝒂𝒓𝒕 𝒃𝒆𝒇𝒐𝒓𝒆 𝒎𝒂𝒌𝒊𝒏𝒈 𝒑𝒖𝒓𝒄𝒉𝒂𝒔𝒆(𝒃𝒖𝒚) 𝒂𝒇𝒕𝒆𝒓 𝒃𝒓𝒐𝒘𝒔𝒊𝒏𝒈(𝒑𝒗) .

Create a ‘𝒗𝒊𝒆𝒘‘ aggregates the number of different behaviour types (pv, fav, cart, buy) for each user and product (user_id and product_id).
Then creat another view to standardise the behaviours into binary values (1 or 0).

    ![behaviour path 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%201.png)

    ![behaviour path 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%202.png)
 This view standardises the behaviours into binary values (1 or 0).

     ![behaviour path 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%203.png)

     ![behaviour path 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%204.png)
Created a view user_behaviour_path to extract users who made a purchase and track their behaviour path.

     ![behaviour path 5](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%205.png)
 This view path_count counts how many users followed each unique behaviour path.

    ![behaviour path 6](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%206.png)
Created a lookup table named path_s for purchase_path codes.

    ![behaviour path 7](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%207.png)
    
•	Helps with readability by providing human-friendly descriptions.
•	Optimises analysis by enabling joins with path_count view.

    ![behaviour path 8](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%208.png)

    ![behaviour path 9](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%209.png)
Inner Join path_count and path_s

    ![behaviour path 10](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/behaviour%20path%2010.png)

### (𝐝) 𝐑𝐅𝐌 𝐌𝐨𝐝𝐞𝐥
Among various customer relationship management (CRM) analytical models, the RFM model is one of the most widely referenced. 
This model evaluates customer value based on three key indicators: 
•	Recency (the time since the last purchase)
•	Frequency(the total number of purchases)
•	Monetary value (the total amount spent)

Since this dataset does not include purchase amounts, customer value is assessed here using only:
•	purchase frequency
•	recency of purchase 

* Search and store the customer's most recent purchase time and spending amount.

    ![rfm 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%201.png)

    ![rfm 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%202.png)

    ![rfm 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%203.png)

* Segment users based on purchase frequency.

    ![rfm segment 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20segment%201.png)

    ![rfm segment 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20segment%202.png)

* Segment users based on their most recent purchase time.

    ![rfm recency 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20recency%201.png)

    ![rfm recency 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20recency%202.png)

    ![rfm recency 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20recency%203.png)

* Calculate the composite score and segment customers into tiers.

    ![rfm model 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20model%201.png)

    ![rfm model 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/%20%20rfm%20model%202.png)

    ![rfm model 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20model%203.png)

    ![rfm model 4](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/rfm%20model%204.png)

## （3）Product data 

### (a) Product Rank by Popularity
Product popularity can be ranked based on views, add-to-cart actions, favourites, and purchases. Here, the ranking is based solely on views. 

Three categories are summarized:
•	products with the highest views 
•	categories with the highest views
•	products with the highest views in each category

(sql)
CREATE TABLE popular_categories(
category_id INT,
pv INT);

(sql)
CREATE TABLE popular_products(
product_id INT,
pv INT);

(sql)
CREATE TABLE popular_cateproducts(
category_id INT,
product_id INT,
pv INT);

* 𝐓𝐨𝐩 𝟏𝟎 𝐜𝐚𝐭𝐞𝐠𝐨𝐫𝐢𝐞𝐬 𝐛𝐲 𝐯𝐢𝐞𝐰𝐬

    ![Top 10 categories 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Top%2010%20categories%201.png)

    ![Top 10 categories 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Top%2010%20categories%202.png)

* 𝐓𝐨𝐩 𝟏𝟎 𝐩𝐫𝐨𝐝𝐮𝐜𝐭𝐬 𝐛𝐲 𝐯𝐢𝐞𝐰𝐬

    ![Top 10 products by views](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Top%2010%20products%20by%20views.png)
  
* 𝐓𝐨𝐩 𝟏 𝐩𝐫𝐨𝐝𝐮𝐜𝐭𝐬 𝐢𝐧 𝐞𝐚𝐜𝐡 𝐓𝐨𝐩 𝟏𝟎 𝐜𝐚𝐭𝐞𝐠𝐨𝐫𝐢𝐞𝐬  𝐫𝐚𝐧𝐤 𝐛𝐲 𝐯𝐢𝐞𝐰𝐬

    ![top product by cate 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/top%20product%20by%20cate%201.png)

    ![top product by cate 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/top%20product%20by%20cate%202.png)

### (b)Product Rank by Conversion Rate
Conversion rate, which is purchase rate. 
•	product conversion rate
•	category conversion rate

* Product conversion rate:

    ![Product conversion rate 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Product%20conversion%20rate%201.png)

    ![Product conversion rate 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Product%20conversion%20rate%202.png)

    ![Product conversion rate 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Product%20conversion%20rate%203.png)

* Category conversion rate:

    ![Category conversion rate 1](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Category%20conversion%20rate%201.png)

    ![Category conversion rate 2](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Category%20conversion%20rate%202.png)

    ![Category conversion rate 3](https://github.com/PennyLi123/Alibaba-E-Commerce-User-Analysis/blob/main/readme%20pictures/Category%20conversion%20rate%203.png)

# Summary
Alibaba Taobao User Behaviour Tableau Dashboard

### Feel Free to use the interactive [dashboard.](https://public.tableau.com/app/profile/penny.li5621/viz/AlibabaE-commerceUserBehaviourAnalysis/Dashboard1)

𝐒𝐭𝐚𝐛𝐥𝐞 𝐓𝐫𝐚𝐟𝐟𝐢𝐜 𝐰𝐢𝐭𝐡 𝐇𝐢𝐠𝐡 𝐑𝐞𝐭𝐞𝐧𝐭𝐢𝐨𝐧:
Website traffic is stable with a high retention rate and strong user engagement. Traffic is higher on weekends compared to weekdays, with a noticeable increase on December 2nd and 3rd, likely due to the pre-sales campaign for December Winter Sale.
𝐂𝐥𝐞𝐚𝐫 𝐁𝐞𝐡𝐚𝐯𝐢𝐨𝐫𝐚𝐥 𝐏𝐚𝐭𝐭𝐞𝐫𝐧𝐬:
User activity peaks during two golden time periods: 10:00-17:00 and 20:00-00:00, when users are most active.
𝐈𝐦𝐩𝐚𝐜𝐭 𝐨𝐟 𝐀𝐝𝐝-𝐭𝐨-𝐂𝐚𝐫𝐭 𝐨𝐧 𝐒𝐚𝐥𝐞𝐬:
Adding products to the cart significantly influences purchase volume, indicating it is a crucial step in the conversion process.
𝐏𝐨𝐩𝐮𝐥𝐚𝐫 𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐢𝐞𝐬 𝐨𝐧 𝐓𝐚𝐨𝐛𝐚𝐨:
Taobao features standout popular product categories, drawing considerable attention from users.

