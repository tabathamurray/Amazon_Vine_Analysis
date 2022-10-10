### Amazon_Vine_Analysis
## Deliverable 3: A Written Report on the Analysis

**Overview of the analysis:** The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon vine program. Utilizing PySpark, performing ETL of the data, AWS connection, PostgreSQL, and Pandas, we will determing if there are any bias towards favorable reviews from Vine members. 

**Results:** Using bulleted lists and images as support, you should address the following questions.

* How many total reviews were there for a review that was or wasn’t written as part of the Vine program? 
*
Total Count Paid = 170
Total Count Unpaid = 37,840

* How many 5 star reviews were there for a review that was or wasn’t written as part of the Vine program?
* 
Total Count Paid 5 Star = 65
Total Count Unpaid 5 Star = 20,612

* What is the total percentage of 5 star reviews for or a review that was or wasn’t written as part of the Vine program?
* 
Percentage Paid 5 Star = 38.24%
Percentage Unpaid 5 Star = 54.47%

**Summary:** For this particular sample, this data shows the 5 star rating is not directly tied to whether or not the reviewer was paid. The other star ratings could be analyzed to see if there is any correlation to the the 1 star reviews. 
