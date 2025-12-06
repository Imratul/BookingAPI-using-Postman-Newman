# BookingAPI-using-Postman-Newman

This repository highlights comprehensive API testing of booking operations using Postman and Newman. It includes tests for creating, reading, updating, and deleting bookings via defined API endpoints.

### Testing Tools 

**Postman** – Used for creating and testing API requests.
**Newman** – Used for running Postman collections via command line, automating tests, and generating reports.

### API Testing Coverage
### Create Booking

Create Booking is used to send a **POST** request to the server to create a new booking or reservation. This request carries all required details—such as guest information, price, dates, and additional needs—in the request body, enabling the server to process and store a new booking in its database.

![Alt Text](CreateID.png)

![Alt Test](CreateID2.png)

![Alt Test](CreateID3.png)


### Get Booking

The **GET** method is used to retrieve data from a server or API endpoint. It fetches information from the server without modifying anything, allowing users to view or read data such as user profiles, product listings, or any other resource available on the server.

![Alt Text](BookingID.png)


### User-Auth (Token Generation)

The **Auth** method is used to authenticate and authorize access to protected API endpoints. It enables users to include credentials, API keys, or authentication tokens in the request headers to verify their identity and access restricted data or actions.

![Alt Text](Automated_Auth.png)


### Update Booking

The **Update** method uses a **PUT** or **PATCH** request to modify existing data on the server. It enables users to change specific fields or properties of a resource without replacing the entire entry, allowing for efficient and precise updates.

![Alt Text](Update.png)


### Delete Booking

The **Delete** method sends a request to a server or API endpoint to remove a specific resource. It enables users to delete data entries, records, or other resources from the server, permanently removing them from the system.

![Alt Text](DeleteBooking.png)
