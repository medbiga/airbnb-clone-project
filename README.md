# airbnb-clone-project
The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.

# Team Roles
Product owner (PO): Holds responsibility for a product vision and evolution and Makes sure the final product meets customer requirements.
Project manager (PM): Makes sure a product or its part is delivered on time and within budget Manages and motivates the software development team.
UI/UX designer: Transforms a product vision into user-friendly designs Creates user journeys for the best user experience and highest conversion rates.
Software architect: Designs a high-level software architecture, Selects appropriate tools and platforms to implement the product vision, and Sets up code quality standards and performs code reviews.
Software developer: Engineers and stabilizes the product and Solves any technical problems emerging during the development lifecycle.
Quality assurance (QA) engineer: Makes sure an application performs according to requirements and Spots functional and non-functional defects.
Test automation engineer: Designs a test automation ecosystem and Writes and maintains test scripts for automated testing.
DevOps engineer: Facilitates cooperation between development and operations teams and Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.

# Technology Stack
Django, MySQL, CI/CD, Docker, GitHub.

# Database Design
entities required for this project are Users, Properties, Bookings, Reviews, and Payments.
for Users there are many fiels such as: Fname, Lname, DOB, PhoneNumber, Address.
For Properties, there are PropertyID, location, state.

# Feature Breakdown
user management, property management, booking system.
Property management: managers/owners. In this managers can manage their hotel's related information
User management: customers. In this customers can search and book a hotel.
Booking system: Here all current and old booking details are shown to the user. Both managers and customers use this service.

# API Security
Users

GET /users/ - List all users
POST /users/ - Create a new user
GET /users/{user_id}/ - Retrieve a specific user
PUT /users/{user_id}/ - Update a specific user
DELETE /users/{user_id}/ - Delete a specific user
Properties

GET /properties/ - List all properties
POST /properties/ - Create a new property
GET /properties/{property_id}/ - Retrieve a specific property
PUT /properties/{property_id}/ - Update a specific property
DELETE /properties/{property_id}/ - Delete a specific property
Bookings

GET /bookings/ - List all bookings
POST /bookings/ - Create a new booking
GET /bookings/{booking_id}/ - Retrieve a specific booking
PUT /bookings/{booking_id}/ - Update a specific booking
DELETE /bookings/{booking_id}/ - Delete a specific booking
Payments

POST /payments/ - Process a payment
Reviews

GET /reviews/ - List all reviews
POST /reviews/ - Create a new review
GET /reviews/{review_id}/ - Retrieve a specific review
PUT /reviews/{review_id}/ - Update a specific review
DELETE /reviews/{review_id}/ - Delete a specific review

# CI/CD Pipeline
Automated pipelines for testing and deploying code changes.
