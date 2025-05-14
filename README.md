# Customer-Complaints - PowerBI Project
Used Power BI to analyze customer complaint relating to banking issues.

**Objective:**

Analyze the complaint dataset to find out what the most complaints are, the channels used, the level of responsiveness to complaint, and make recommendations on how to improve overall performance of the banking products. 

**Dataset Used:**
<a href="https://github.com/Folakareem/PowerBI-Customer-Complaints/blob/main/Raw_Data.xlsx">Dataset

**About Dataset:**
This data set contains 62,516 records of banking transactions mainly focusing on complaints from customers, showing dissatisfaction with one or more banking products. There are 9 unique products, ranging from Mortgage, Money transfer, credit reporting, credit or prepaid card, Checking or savings account, Vehicle loan or lease, Debt Collection, Payday loan and Student loan. All of these categorized into subcategories and 76 Issues also categorized into sub issues.  The dataset will be used to identify the complaint trends and major complaints, understand the channel used to log complaints and how to better improve performance. 

**KPIs**
1.	The number of total complaints, products and issues.
2.	Identify complaint trend 
3.	Identify the year when most complaints were logged.
4.	The product with the most complaints
5.	Th state where complaints were logged the most
6.	The channel used to make the most complaints
7.	The product, sub product and state with the most complaints
8.	In the last three years, identify the trends of complaints amongst the Product and Sub products.
9.	Identify the company response rate.

**Process:**
1.	Load, clean and transform the Data
2.	Promoted headers, change data type to the right data type
3.	Identify unique products and Issues, removed duplicate
4.	Label unique products and issues table with index number
5.	Identify unique responses, append response to create one response table (Append tables Company response to consumer and Company public response)
6.	Create a Fact table (Customer Complaint) and Dimension tables (Product, Issue, Public response, Channel)
7.	Merge dimension table with the fact table, remove duplicate columns
8.	Create a Date Table with Month No, Year, Month Name, Day of week, Week Number, Day and Quarter
9.	Check and review model relationships
10.	Create a dashboard to analyze data.

**Dashboard Interaction**
<a href="https://app.powerbi.com/groups/me/reports/a9b98b03-29fc-45d0-a089-be81310b10c1?experience=power-bi">View Dashboard

**Dashboard:**
![Dashboard](https://github.com/user-attachments/assets/b6a12d38-7983-43f1-96cb-89d2ddd7f4a3)

**Project Insight:** 
1.	Total complaints 62,520, total products including sub products 47, total issues including sub issue 211
2.	Complaint trended upwards from 2019 – 2022.
3.	The year 2022 had the highest number of complaints totaling 12,936
4.	The checking and savings account holder had the highest number of complaints. Majority being the checking account holders
5.	California had the highest complaint, totaling 13,709, followed by Florida and Texas.
6.	The Web channel had the highest complaint totaling 9,823. Most members complained via the web channel.
7.	The checking account holder, with the same sub product as the checking account, living in California, had the highest number of complaints, totaling 4,474 complaints.
8.	Members had responded “YES” to timely response by the bank to 23,237 complaints.

**Conclusion and Recommendation:**
1.	Checking accounts holders seem to have the highest overall complaint. 
Assumptions: Make inquiry whether a new product feature added to the checking account made it impossible for members to use the product seamlessly? Or new fees for running the account have resulted in numerous complaint. In the absence of this information, these assumptions were made. 
2.	The state of California had the highest complaint, for onsite banking services, assumptions were made about banking staff services or new state laws affecting the bank products may have impacted customers 
3.	The web channel appear to be working impeccably for members to log complaints, the bank should continue to make this channel free from data and security threats by investing in cyber security.





    








