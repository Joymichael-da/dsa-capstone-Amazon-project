# dsa-capstone-Amazon-project
### Goals And Objectives
We had a 3month virtual training session with Incubator Hub as our trainer.This repository is a project given to the student to test our knowledge of what we have learnt in the past months.This project contains a Amazon Product Review created in an Excel format.The project aims to analyze product and customer review data for a e-commerce platform to generate insights that can guide product improvement,marketing strategies,and customer engagement.My goal is;
- To understand customer behavior through their reviews
- Track product sales
- Identify key trends in purchases
- build an excel dashboard.

### Methodology and Tools Needed
- Microsoft Excel for Data cleaning,calculations and Visualization.
- Pivot table for summarizing and analysing data.
- Github for submission.

### Data Source and Description
The primary source of data used here is Amazon product review.csv and this is an open source data provided by our instructors.The dataset has a total records of 1465 rows and total fields of 16 columns.Contained in the dataset is ;
- Product details: name,category, price,discount and ratings
- Customer engagement: user reviews,titles and content.

### Analysis and Results
I started my analysis by;

Browsing through the data to understand what I have and identify what is needed.

I put my dataset in a table format to help excel recognise my dataset as a structured table.

I cleaned my dataset by;

a)checking for blanks ( I filled in 2 blanks in the rating_count colunm with 00).

b)ckecking for duplicates (I identified 65 duplicates left with 1400 unique values).

c)I used delimeter(|) for my category colunm in order to extract only the main category needed.

d) I added some calculated columns

e) I deleted some columns that were not needed for the analysis.

#### Results
1) Average discount percentage by product category
   
    ![Screenshot (37)](https://github.com/user-attachments/assets/eca5cfc4-2f6c-4888-a487-b5ba04feb928)

   Product with the highest discount average discount category is Home improvements,Toys & games had no discount offer.

 2) Number of products listed under each category

     ![Screenshot (38)](https://github.com/user-attachments/assets/a6ecd65a-1ecd-4474-917a-259c7a414165)

    Electronics had the highest number of product,Car and Motorbike,Toys and Games,Health and Personal Care were the least number of product.

3) The total number of reviews per category

    ![Screenshot (39)](https://github.com/user-attachments/assets/e0706bdc-6529-4a54-b21a-810b8cdf1510)

    Electronics had the most review, car and motorbike had the least number of review.

4) Products with the highest  average rating

  a)	Amazon Basics Wireless Mouse.
   
  b)  Syncwire LTG to USB Cable for Fast Charging Compatible with Phone.
  
  c) REDTECH USB-C to Lightning Cable 3.3FT.

  ![image](https://github.com/user-attachments/assets/d2ecff6c-3b5d-4370-ae50-5320031e404e)

   This 3 products with the higest rating are the most liked/prefferd product.

5) Average actual price vs the discounted price by category

   ![Screenshot (40)](https://github.com/user-attachments/assets/db3aca34-ebc5-45c2-9f38-503747f38297)

    This table shows Toys and Games was not offered at a discount price.

6) Product with the highest number of reviews.
     
 a)AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot.		  

 b)Amazon Basics High-Speed HDMI Cable, 6 Feet. 

 c)Amazon Basics High-Speed HDMI Cable, 6 Feet (2-Pack),Black.

 d)AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot.	

![image](https://github.com/user-attachments/assets/96ebcd83-69d3-402b-a43a-285b4dc7fbd4)

7) Products that have a discount of 50% or more

   This was analysed using the formular =COUNTIF(discount%_range,(">=50").The result showed that 694 products had a discount of 50% and more for its sales.

8) Distribution of product ratings

   ![Screenshot (42)](https://github.com/user-attachments/assets/6986f4dd-95c5-4249-b509-001a447e8f9b)

9) Total potential revenue

    ![Screenshot (43)](https://github.com/user-attachments/assets/c1911c28-6588-44ea-a53d-00f06152cc72)

   From the discount sales conducted Electronics has the highest potential revenue.

10) Number of unique products per price range bucket

    ![Screenshot (44)](https://github.com/user-attachments/assets/2ed7cf9b-8e93-4027-a1ea-91ef6646f3f6)

11) Relationship of rating to the level of discount

     ![Screenshot (45)](https://github.com/user-attachments/assets/9c2973cd-7324-4cef-97fd-eb2ac1c7acaa)

     The level of discount does not affect the rating,as the rating for all product ranges between 4.0 - 4.2

12) Number of product with fewer than 1000 reviews

    This was analysed using the formular =COUNTIF(rating_count_range,"<1000").The result showed that ###313 products had less than 1000 reviews.
  
13)  Product with the highest discounts

    ![Screenshot (47)](https://github.com/user-attachments/assets/088bca1c-2f1c-49a1-87bd-ccb9bab4bf9c)

14) Top 5 products in terms of rating and number of reviews combined

a) AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot	Electronics	 

b) Amazon Basics High-Speed HDMI Cable, 6 Feet - Supports Ethernet, 3D, 4K video,Black	Electronics	 

c) Amazon Basics High-Speed HDMI Cable, 6 Feet (2-Pack),Black	Electronics	

d) AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot	Electronics	

e) boAt Bassheads 100 in Ear Wired Earphones with Mic(Taffy Pink)	Electronics	

![image](https://github.com/user-attachments/assets/ae5f9f47-b6e0-47d8-9d14-d068cee8370e)




### Excel Dashboard
- 																
																
																
																
																
																
																
																




