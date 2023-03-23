# Capstone-Project

## Background
Spot Health is a company that provides home health testing services for a variety of conditions, including lab-analyzed blood, urine, and saliva tests. Their tests can be ordered online or purchased at local Costco stores, and are designed to be performed at home. Results are typically available within a few days after the samples are sent back to the lab. Since its founding in 2021, Spot Health has delivered over 9,000 test kits, with a success rate of 89.46%. The company aims to provide affordable, convenient, and confidential testing options for individuals who may not have access to traditional healthcare services or who prefer the privacy and convenience of testing at home.

## Objective
Based on the information provided by the company, out of a total of 9,881 tests, 8,840 were successful, 195 exceeded stability, 302 were hemolyzed, and 544 were QNS (quantity not sufficient). In light of this information, our goals moving forward might include the following to improve perspective successful test and result rate:
<br> Descriptive Analysis
<br /> - Data Visualization
<br> Predictive Analysis
<br /> - Constructing Classification Model (Random Forest / Neural Network)
<br> Prescriptive Analysis
<br /> - Understanding Customer Behaviors 
<br /> - Pre-Acting and Providing targeted services

## Data Dictonary
Demographics 
  <br /> - ID (Hash of Patient MRN)
  <br /> - Zipcode (Convert to Distance from Test Centers)
  <br /> - Age (Converted from DoB)
  <br /> - Sex
  
Kit Information
  <br /> - Type of Kit
  <br /> - Specimen Type
  <br /> - Client ID
  
Behavioral Information
  <br /> - Datetime Kit Received
  <br /> - Datetime Registered (When the Kit is Used)
  <br /> - Datetime Sample Sent in
  <br /> - Datetime Resulted
  
Outcome Information
  <br /> - Status
    <br /> - Resulted
   <br /> -  Partially Resulted
   <br /> -  Failed (Not enough Blood / Hemolyzed / Exceeds Stability)
    
    
    
    
    
    
