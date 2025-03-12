# Booking-API Performance Testing with Jmeter
### In this project, I have used Jmeter to find the actual throughput(TPS), expected TPS and Bottleneck TPS for a site with a given number of users and time. Load test and Stress test(s) were carried out to find TPS values.

## Site Tested
https:restful-booker.herokuapp.com

### Scenario:
120,000 users over a 12-hour period log in, create a booking, and search for the
booking. 

### Load
- Users: 120000
- Time: 12 Hours
- Error Threshold: 0.5%
- Timer: Gaussian Random Timer (Deviation 2000ms, Constant delay 500ms)

## Tools Used
  - Apache Jmeter

## How to run this project
- Clone this project
- Open the .jmx file using JMeter

### TPS & Bottleneck Calculations 
Link to Excel: https://docs.google.com/spreadsheets/d/1uP1Y8Ru0Ijzi4sHCAEg7oMJMM5hCTwxU/edit?usp=sharing&ouid=105043411924406613334&rtpof=true&sd=true

## Expected Throughput
![Screenshot 2025-03-12 010022](https://github.com/user-attachments/assets/e1ec2fb6-d29b-4141-ba9c-9e5ba0614cf3)

## Load Test Results 
![Screenshot 2025-03-12 010551](https://github.com/user-attachments/assets/9c350f11-5caf-44ff-8243-9658ba68d6cd)

## APDEX, Statistics and Results Summary of Load Test
![image](https://github.com/user-attachments/assets/c993529b-95f3-4ecd-ac00-f2081c5ec57f)

## Stress Test Results
![Screenshot 2025-03-12 153317](https://github.com/user-attachments/assets/e23602a5-9269-4492-aef2-3771c7431649)

## Bottleneck Throughput
![image](https://github.com/user-attachments/assets/d41f0901-899e-430c-bb23-c4ee55e03ad3)




## APDEX, Statistics and Results Summary of Stress Test
![Screenshot 2025-03-12 153913](https://github.com/user-attachments/assets/7ed9d97b-8299-4ea7-ae2b-743dbd75ce9a)





