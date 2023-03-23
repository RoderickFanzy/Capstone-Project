# Capstone-Project

## Background
Spot offers home health testing services for a variety of conditions, including blood test, urine test and more. Their tests can be ordered online and purchased in local Costco and performed at home, with the results typically available within a few days after the samples are sent back to the lab. Since the foundation of the company, it has successfully delivered and received over 9000 packages of test kit with a successful test rate of 89%

## Objective
According to the analysis provided by the company, among 9881 total tests, 8840 tests are successful, 195 exceeds stability, 302 tests are hemolyzed, and 544 tests are QNS. Our goals will be summarized as follow:
Visualizing the geographical distribution of Spot Test Kit Users

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
    
    
    
    
    
    
