 
# API Test Automation Project

## How to run this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run API_Test_Automation.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run API_Test_Automation.postman_collection.json -e API_Test_Automation.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-html
```
- Newman htmlextra Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://docs.google.com/document/d/1YyzPMbEu6eEMFrvp-WHiJW-SvDTJvikqx1QGyyFgRXw/edit?usp=sharing

## Test case list:
1. ### Token Generate
	> In this request need to generate token as per documentaion and need to validate the following field values:
 	1. > Token data
    2. > Status code validation
    3. > Response Time Validation
2. ### Create(Booking)
	> Create Data Sets Using the Dynamic Random Variables 
    > In this test case need to validate the following field
    1. > Response time validation
    2. > Status Code validation

3. ### FetchBookingData
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > totalprice
 	4. > depositpaid
    5. > Content-Type value test
    6. > checkin
    7. > checkout
    8. > Response Time validation
    9. > Connection header present
    10. > Content-Type header present
    

4. ### UpdateBookingInfo
	> In the test case need to validate the following field values:
	1. > checkin
 	2. > checkout
	3. > totalprice
 	4. > Status code validation
    5. > Status code validation
5. ### FetchUpdatedData
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > totalprice
 	4. > depositpaid
    5. > Content-Type value test
    6. > checkin
    7. > checkout
    8. > Response Time validation
    9. > Connection header present
    10. > Content-Type header present

6. ### Delete Booking Details
	> In the test case you need to validate the following field values:
	1. > Only Message

## Newman Report Summary:
![Newman Report Summary](https://github.com/mamuneee78/API_Test_Automation_Project/blob/main/Newman%20HTML%20report%20dashboard.png)

![Newman Report Summary](https://github.com/mamuneee78/API_Test_Automation_Project/blob/main/API%20Requests.png)
![Newman Report Summary](https://github.com/mamuneee78/API_Test_Automation_Project/blob/main/Request%20details.png)
![Newman Report Summary](https://github.com/mamuneee78/API_Test_Automation_Project/blob/main/Failure%20reason.png)
