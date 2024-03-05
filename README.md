# **API Testing Project: Booking ID**

This repository showcases API testing for booking functionalities using Postman and Newman. The focus is on creating, retrieving, updating, and deleting bookings through specific API endpoints.

## **Testing Tools:**

**Postman:** Used for sending API requests, managing test collections, and inspecting responses.

**Newman:**  Utilized for running tests from the command line and generating reports in different formats (e.g., HTML, JSON).

## **Testing Coverage:**

#### **CRUD Operations:** The project encompasses tests for the following functionalities-

Create bookings (POST)

Retrieve bookings (GET)

Authenticate users (POST)

Update booking details (PUT)

Verify update success (PUT)

Delete bookings (DELETE)

Verify deletion success (DELETE)

Handle array-based data (example)

**Booking_Id_api_tests:** This file describes the API testing project.

**Postman_Collections:** This folder (if applicable) holds Postman collections for different testing scenarios.

**Newman_Report:** This folder (if applicable) contains Newman-generated test reports.

## **Create_Booking**
Create Booking is typically used to send a POST request to a server to create a new booking or reservation. This POST request includes the necessary data (such as guest details, room type, dates, etc.) in the request body, allowing the server to process and create a new booking entry in its database.

<img width="675" alt="Create Body" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/95056fb6-0af4-44fd-b9d3-f45388b2af7c">

<img width="675" alt="Create_prerequest script" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/e57c14f6-3a11-46d7-a435-18f663dc69d0">


## **Get_Booking**
In Postman, a GET method is used to retrieve data from a server or API endpoint. It fetches information from the server without modifying anything, allowing users to view or read data such as user profiles, product listings, or any other resource available on the server.

<img width="675" alt="Get" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/cffcd818-4758-4ec7-8360-8cc1d069bd7f">

## **Auth_User**
In Postman, an Auth method is used to authenticate and authorize access to protected resources on a server or API endpoint. It allows users to include authentication tokens, API keys, or credentials in the request headers to verify their identity and gain access to restricted data or operations.

<img width="675" alt="Auth" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/0bbac20f-68ea-40c2-98ed-5a5cfb483b07">

## **Update_Booking**
 Update method is used to send a PUT or PATCH request to a server to modify existing data or resources. It allows users to update specific fields or properties of a resource without replacing the entire resource, ensuring efficient and targeted updates to the server's data.
 
 <img width="675" alt="Update" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/15adf7f8-0a52-43c2-ae1b-67edf88b6e7c">

## **Verify_Update**
verify update request API" is used to confirm the successful update of a resource. It involves sending a PUT or PATCH request to modify the resource and then sending a subsequent GET request to ensure that the changes have been applied correctly on the server. This verification step helps ensure the accuracy and completion of the update process.

## **Delete_Booking**
Delete method is used to send a request to a server or API endpoint to remove a specific resource. It allows users to delete data entries, records, or other resources from the server's database or storage, effectively removing them from the system.

<img width="675" alt="Delete" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/84b7bb7c-0daf-476c-86e0-5764144bb0bd">

## **Verify_Delete**
Verify delete method" is typically used to confirm the successful deletion of a resource. It involves sending a DELETE request to remove the resource and then sending a subsequent GET request to ensure that the resource has been properly deleted from the server. This verification step helps ensure the accuracy and completion of the deletion process.

## **Array_Example**
Array Example is used to demonstrate and test API requests and responses involving arrays or lists of data. It provides examples of how to structure requests with array parameters or how to handle responses that include arrays of data, helping users understand and work with array-related functionalities in their API interactions

<img width="675" alt="Array" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/e01a5945-4a39-483a-8d05-b43a1c2d1266">

## **Newman_Report**
Newman report" feature is used to generate detailed test reports for API collections run using the Newman command-line tool. It provides a summary of test results, including pass/fail statuses, response times, and error details, allowing users to analyze and share test results with team members or stakeholders.

<img width="428" alt="Newman_Report" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/e58c4526-c87b-4909-936e-eb254c3d987d">
<img width="725" alt="Newman_Report2" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/0419dc2a-deb0-4e91-92e0-1c847bef0dbf">

## **Newman_RunCommand**
Newman Run Command is used to execute API collections from the command line using the Newman tool. It allows users to automate the execution of tests, run them in CMD pipelines, and generate detailed reports, enhancing the efficiency and scalability of API testing processes.

<img width="630" alt="Newman_RunComand" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/6c126b56-ae65-458e-8fec-4d5f2501dcc3">

## **Data.csv:**
Data.csv File is used to demonstrate and test API requests and responses involving CSV (Comma-Separated Values) data format. It allows users to import CSV files, use the data in requests, and test how the API handles CSV data, providing a practical example for working with CSV-based APIs.This file (if applicable) contains sample data used during testing, connected to the environment using variables.

<img width="675" alt="Data CSV" src="https://github.com/ismail-hossain12012/Booking-ID-API/assets/76116674/53fd2886-2409-46fc-9075-20791c084b3b">
