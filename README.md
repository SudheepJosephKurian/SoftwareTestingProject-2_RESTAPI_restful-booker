# RESTful Booker API Project

## Overview

The RESTful Booker API is a simple API that allows users to create, retrieve, update, delete, and partially update bookings. It also supports user authentication. This project contains test cases for verifying the functionality, security, and performance of the API.

## API Documentation

The complete API documentation can be found [here](https://restful-booker.herokuapp.com/apidoc/index.html).

## Endpoints

- **Health Check**: `GET /ping`
- **Create Booking**: `POST /booking`
- **Get Booking**: `GET /booking/{id}`
- **Update Booking**: `PUT /booking/{id}`
- **Partial Update Booking**: `PATCH /booking/{id}`
- **Delete Booking**: `DELETE /booking/{id}`
- **Create Token**: `POST /auth`

## Setup

### Prerequisites

- [Postman](https://www.postman.com/downloads/)
- [JMeter](https://jmeter.apache.org/download_jmeter.cgi)
- [OWASP ZAP](https://www.zaproxy.org/download/)

### Running the Tests

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/restful-booker-api.git
   cd restful-booker-api

2.	Setup Postman:
o	Import the Postman collection and environment from the postman directory.
o	Run the collection to execute the test cases.

3.	Run Performance Tests:
o	Open JMeter and load the test plan from the jmeter directory.
o	Execute the test plan to run performance tests.

4.	Run Security Tests:
o	Open OWASP ZAP.
o	Import the ZAP project from the zap directory.
o	Run the security scan.

### Test Plan
Testing Types
1.	Functional Testing: Verify each endpoint works as expected.
2.	Integration Testing: Ensure all API components work together correctly.
3.	Security Testing: Test for vulnerabilities and ensure secure access using authentication tokens.
4.	Performance Testing: Measure the performance of the API under various loads.
5.	Error Handling Testing: Verify the API returns appropriate error messages and status codes.

![image](https://github.com/SudheepJosephKurian/SoftwareTestingProject_RESTAPI_restful-booker/assets/165445324/a36109c8-4bff-4467-979b-522030fb0918)



### Test Cases
Health Check
1.	Verify Health Check Endpoint: Ensure the health check endpoint is accessible and returns a 200 OK status.
Create Booking
2.	Create Booking with Valid Data: Create a new booking with valid data.
3.	Create Booking with Only Required Fields: Create a new booking with only the required fields.
4.	Create Booking with Special Characters: Create a booking with special characters in the fields.
Get Booking
5.	Get Booking by Valid ID: Retrieve a booking using a valid booking ID.
Update Booking
6.	Update Booking with Valid Data: Update an existing booking with valid data.
Delete Booking
7.	Delete Booking by Valid ID: Delete a booking using a valid booking ID.
Partial Update Booking
8.	Partial Update Booking with Valid Data: Partially update an existing booking with valid data.
Create Token
9.	Create Token with Valid Credentials: Create an authentication token with valid credentials.
Additional Test Cases
10.	Create Booking with Maximum Field Lengths: Create a booking with the maximum allowable length for each field.
11.	Create Booking with Zero Price: Create a booking with a total price of zero.
12.	Get Booking with Valid Dates: Retrieve a booking with valid check-in and check-out dates.
13.	Update Booking with Extended Stay: Update a booking to extend the stay period.
14.	Create Token with Another Valid User: Create an authentication token with another set of valid credentials.
15.	Get Booking with Additional Needs: Retrieve a booking that has additional needs specified.
16.	Create Booking with Multiple Additional Needs: Create a booking specifying multiple additional needs.
17.	Create Booking with Non-English Characters: Create a booking with non-English characters in the fields.
18.	Update Booking with Reduced Stay: Update a booking to reduce the stay period.
19.	Partial Update Booking with Lastname: Partially update a booking by changing the last name.
20.	Create Booking with Future Dates: Create a booking with check-in and check-out dates in the future.
21.	Create Booking with No Additional Needs: Create a booking without specifying any additional needs.
22.	Get Booking After Update: Retrieve a booking after it has been updated to verify changes.
23.	Create Booking with Leap Year Dates: Create a booking with check-in and check-out dates during a leap year.
24.	Partial Update Booking with Price: Partially update a booking by changing the total price.
25.	Create Token with Edge Case Username: Create an authentication token with an edge case username.

Contribution
________________________________________
Author: Sudheep Joseph Kurian
