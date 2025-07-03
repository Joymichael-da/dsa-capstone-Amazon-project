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
Browsing through the data to understand what I have and identify what is needed
I put my dataset in a table format to help excel recognise my dataset as a structured table
I cleaned my dataset by a)checking for blanks( I filled in 2 blanks in the rating_count colunm with 00)
b)ckecking for duplicates (I identified 65 duplicates left with 1400 unique values)
c)I used delimeter(|) for my category colunm in order to extract only the main category needed.
d) I added some calculated columns
e) I deleted some columns that were not needed for the analysis.

#### Results
- Average discount percentage by product category
- Number of products listed under each category
- Total number of reviews per category
4) Products with the highest  average rating

  a)	Amazon Basics Wireless Mouse.
   
  b)  Syncwire LTG to USB Cable for Fast Charging Compatible with Phone.
  
  c) REDTECH USB-C to Lightning Cable 3.3FT.

![image](https://github.com/user-attachments/assets/d2ecff6c-3b5d-4370-ae50-5320031e404e)

This 3 products with the higest rating are the most liked/prefferd product.

5) Average actual price vs the discounted price by category

6) Product with the highest number of reviews
     
 a)AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot.		  

 b)Amazon Basics High-Speed HDMI Cable, 6 Feet. 

 c)Amazon Basics High-Speed HDMI Cable, 6 Feet (2-Pack),Black.

 d)AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot.	

![image](https://github.com/user-attachments/assets/96ebcd83-69d3-402b-a43a-285b4dc7fbd4)


  
7) Products that have a discount of 50% or more

   This was analysed using the formular =COUNTIF(discount%_range,(">=50").The result showed that 694 products had a discount of 50% and more for its sales.

8) Distribution of product ratings

9) Total potential revenue

10) Number of unique products per price range bucket

11) Relationship of rating to the level of discount


12) Number of product with fewer than 1000 reviews

    This was analysed using the formular =COUNTIF(rating_count_range,"<1000").The result showed that 313 products had less than 1000 reviews.
  
13)  Product with the highest discounts
    
14) Top 5 products in terms of rating and number of reviews combined

a) AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot	Electronics	 

b)	Amazon Basics High-Speed HDMI Cable, 6 Feet - Supports Ethernet, 3D, 4K video,Black	Electronics	 

c) Amazon Basics High-Speed HDMI Cable, 6 Feet (2-Pack),Black	Electronics	

d) AmazonBasics Flexible Premium HDMI Cable (Black, 4K@60Hz, 18Gbps), 3-Foot	Electronics	

e) boAt Bassheads 100 in Ear Wired Earphones with Mic(Taffy Pink)	Electronics	

![image](https://github.com/user-attachments/assets/ae5f9f47-b6e0-47d8-9d14-d068cee8370e)




### Excel Dashboard
- 																
																
																
																
																
																
																
																




