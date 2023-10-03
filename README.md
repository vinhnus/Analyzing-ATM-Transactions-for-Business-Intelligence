# Analyzing-ATM-Transactions-for-Business-Intelligence

## Introduction
Wisabi Bank is a leading financial institution in Nigeria, headquartered in Lagos with branches in Kano, Rivers State, Enugu, and FCT Abuja. Wisabi Bank provides a wide range of financial services to its customers, including savings accounts, current accounts, loans, and investments. As part of its commitment to improving customer experience and optimizing its operations, Wisabi Bank has engaged you as an external consultant to conduct a data analytics project to analyse its ATM transactions data

## Business Problems
Wisabi Bank wants to answer several business problem questions related to its ATM transactions data, which include:
* What is the average transaction amount by location and transaction type?

* Which ATM location has the highest number of transactions per day, and at what time of the day do the transactions occur most frequently?

* Which age group has the highest number of transactions, and which transaction type do they usually perform?

* What is the trend of transaction volume and transaction amount over time, and are there any seasonal trends or patterns?

* What is the most common transaction type, and how does it vary by location and customer type (Wisabi customer vs. non-Wisabi customer)?

* What is the average transaction amount and transaction frequency per customer by occupation and age group?

* What is the percentage of transactions that are withdrawals, savings, balance enquiries, and transfers, and how does it vary by location and time of day?

* What is the distribution of transaction amounts and transaction frequency, and are there any outliers?

* Which ATM locations have the highest and lowest utilization rates, and what factors contribute to this utilization rate?

* What is the average transaction time by location, transaction type, and time of day, and how does it vary by customer type and occupation?

## Report and Analysis

### ATM transactions
![Screenshot 2023-10-03 190720](https://github.com/vinhnus/Customer-Segment-and-Sales-Prediction/assets/132123952/d0cefa8e-a09d-49e8-abd2-e3ed4e601eaa)

**Utilization Rate**

ATMs in Kano have the highest Utilization Rate (18.6%)

Rivers & Lagos have Utilization Rates greater than 12% (12.7% & 12.2% respectively) while that for Enugu is 11.6%

The FCT has the lowest Utilization Rate (8.5%)

**Relationship between Average Amount and Duaration**

On Average, while the transaction amount is comparatively similar, Withdrawals in Kano have the longest transaction duration (>5 mins) when compared with other states.

Kano, Lagos, and the FCT have longer transaction duration for Deposits (>5 mins) while Rivers has the lowest transaction duration for deposits.(<4 mins)

Kano also has the longest transaction duration for Balance Inquiries and Transfers

Withdrawals have the highest transaction amount on average as expected. Withdrawals and Deposits have longer transaction duration on average while Balance Inquiries have the least transaction duration.

**Daily Transaction Trend**

ATM Transactions in Lagos increase gradually from 6 am and peaks between 3 and 7 pm.

Similar behavior is seen across other states however transactions peak earlier in Kano (around 11 am) and this is sustained till about 5 pm after which activity sharply declines.

Compared to other states, Lagos has significant transactions activity after 7 pm.

**Average Transaction Amount by Month**

We had the highest number of transactions and transaction amount in March

Other months with high transaction activity include January, May, July, October, and December

We had the lowest number of transactions and transaction amount in February

**Average Transaction Amount by State**

On Average, Withdrawals have the highest transaction amounts across all states, next is Transfers, with Deposits have the lowest.

Across all locations, The FCT has comparatively lower Deposit amounts on Average

### Demographic Report

![Screenshot 2023-10-03 191834](https://github.com/vinhnus/Customer-Segment-and-Sales-Prediction/assets/132123952/6f2a58f3-0a29-40cc-b404-40935bd6eb09)

**Transaction Frequency**

Customers between 16-25 years have the highest transaction frequency (260).

Interestingly, customers above 65 years have a higher transaction frequency (216) than the 56 - 65 & 46 - 55 age groups (207 & 205 respectively). 

**Transaction Count**

Across all Age Groups, Withdrawals is the common transaction type (>50%), followed by Transfers (>20%)

Interestingly, Deposits & Transfers account for a significant amount of transactions (>10% each) across all Age Groups

**Porpotions of Transaction Type**

Withdrawls takes about 55.5% of transaction type, following with transfer 22.2%

The remaining are the other two type which is Balance Inquiry and Deposit, around 11,5%

### Recomendation

**Utilization rate** in the FCT is comparatively low. Possible solutions to remedy this include:

Make sure that the ATMs are visible and accessible to customers. This could involve relocating the ATMs to more prominent locations, installing signage, or improving lighting and landscaping around the ATMs.

Offer incentives to customers such as waived transaction fees or cashback rewards.

Use various marketing channels to promote the availability and convenience of the ATM to customers, such as through social media, email newsletters, or in-branch promotions.

Consider offering additional services at the ATM, such as the ability to deposit checks or make cash withdrawals in different denominations.

Conduct surveys or use customer analytics to understand the preferences and habits of customers who use the ATM, and tailor the ATM's services and features to better meet their needs.

**Average Transaction Duration** in Kano is longer when compared to other locations. Possible solutions to remedy this include:

Increase the number of ATMs available in the branch, as this can reduce wait times and congestion at each individual ATM.

Consider upgrading the ATMs to newer models with faster transaction times and more advanced features. This can improve the overall experience for customers using the ATM and may encourage them to use it more often.

Ensure that the ATMs are regularly serviced and maintained to prevent downtime and minimize technical issues that can contribute to longer transaction times.

Analyze transaction data to identify bottlenecks or issues that may be contributing to longer transaction times. This could involve looking at patterns of usage, common user errors, or technical issues that may be slowing down the process.

Provide customers with education on how to use the ATM more efficiently, such as by highlighting common errors to avoid or offering guidance on how to complete transactions more quickly.

**Transactions Activity**

ATMs have significantly reduced activity in the early and late hours of the day (Before 5 am & After 8 pm). Lagos is the only exception as there is still noticeable activity after 8 pm.

Scheduled maintenance should coincide with these periods of reduced activity. 

Additionally, ATMs should have maximum availability especially during the peak activity periods for each bank branch. 

**A significant proportion of transactions (>20%) are either Balance Enquiries or Transfers**. Possible solutions to remedy this include:

Provide customers with education on alternative banking channels such as phone banking or online banking, highlighting the benefits of these channels and how to use them effectively. This could involve providing brochures or other materials in the branch, as well as online resources and tutorials.

Consider offering incentives to customers who use alternative banking channels, such as waiving transaction fees or offering cashback rewards. This can encourage customers to try these channels and may help to shift usage away from the ATM.

Ensure that the phone banking process is simple and straightforward for customers to use, with clear instructions and minimal waiting times.

Continue to monitor customer behavior and analyze usage data to identify areas where usage of alternative banking channels can be improved.

Offer personalized support to customers who may be hesitant to use alternative banking channels, such as providing one-on-one assistance or guidance on how to get started with phone banking or online banking. This can help to build trust and confidence in these channels and may help to shift usage away from the ATM.











