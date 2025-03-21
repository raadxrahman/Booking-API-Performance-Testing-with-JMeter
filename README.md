# Booking-API Performance Testing with JMeter
### In this project, I have used JMeter to find the actual throughput(TPS), expected TPS and Bottleneck TPS for a site with a given number of users and time. Load test and Stress test(s) were carried out to find TPS values.

## Site Tested
https://restful-booker.herokuapp.com
#### Paths:
- /booking
- /booking/<booking_id>

### Scenario:
120,000 users over a 12-hour period log in, create a booking, and search for the
booking. 

### Parameters
- Users: 120000
- Time: 12 Hours
- Error Threshold: 0.5%
- Timer: Gaussian Random Timer (Deviation 2000ms, Constant delay 500ms)

## Tools Used
  - Apache JMeter

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
![image](https://github.com/user-attachments/assets/e41d3f96-6c71-41e2-99bf-edf1aaeb1b46)


## Bottleneck Throughput
![image](https://github.com/user-attachments/assets/096fe0ab-4cc0-480e-8420-dc3906fae586)





## APDEX, Statistics and Results Summary of Stress Test
![Screenshot 2025-03-12 153913](https://github.com/user-attachments/assets/7ed9d97b-8299-4ea7-ae2b-743dbd75ce9a)





