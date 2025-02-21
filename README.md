# Api-testing
Introduction
This project is about testing an API for a booking system using Postman and Newman. It includes different test cases for creating, retrieving, and updating bookings. The tests also include authentication using tokens to ensure secure access.

What This Project Covers
Creating a Booking (POST) Adds a new booking with random test data.
Retrieving a Booking (GET)  Fetches details of a booking using an ID.
Updating a Booking (PUT) Modifies an existing booking using a token.
Generating an Authentication Token (POST) Retrieves a token for secure API requests.
Note: This project does not include deleting a booking or updating with PATCH.

Tools and Technologies Used
Postman  A tool for API testing and automation.
Newman  A command-line tool to run Postman tests.
Postman Environment Variables  Used to store dynamic data for tests.
JSON Reports  Automatically generated test results.

Booking.postman_collection.json  The Postman collection containing all API test cases.
Booking.postman_environment.json  The environment file with variable settings.
Booking-2025-02-15-15-18-56-873-0.html,newman-run-report-2025-02-15-15-18-03-888-0.html - A test report generated after running the tests.

Expected Results
All API requests should return the expected data.
HTTP status codes should be correct (200, 201, etc.).
The authentication token should be valid and required for updates.
Updated bookings should reflect correctly when retrieved.

Conclusion
This project helps in understanding API testing using Postman and Newman. It covers the basic operations needed to interact with an API in an automated way.