Library Management System
A comprehensive Django-based library management system designed to handle user management, book management, and administrative tasks. This system supports complex operations including borrowing, returning books, managing fines, and analytics.

Features
User Management: Manage users with roles like regular and premium.
Book Management: Add, update, and delete books and manage their availability.
Author Management: Maintain author information.
Library Branch Management: Organize different branches of the library.
Borrowing and Returning: Handle book borrowing and returning, including overdue tracking and fines.
Fine Management: View, pay, and manage fines.
Analytics: Retrieve data on most borrowed books, active users, overdue books, and fine statistics.
Technology Stack
Python: 3.x
Django: 3.x or later
Django REST Framework: For API endpoints
SQLite: For database (SQLite is used by default)
Locust: For performance testing
drf-yasg: For API documentation
API Endpoints
Books
List Books: GET /books/
Retrieve Book Details: GET /books/{id}/
Create a Book: POST /books/
Update a Book: PUT /books/{id}/
Delete a Book: DELETE /books/{id}/
Authors
List Authors: GET /authors/
Retrieve Author Details: GET /authors/{id}/
Create an Author: POST /authors/
Update an Author: PUT /authors/{id}/
Delete an Author: DELETE /authors/{id}/
Library Branches
List Library Branches: GET /library-branches/
Retrieve Branch Details: GET /library-branches/{id}/
Create a Branch: POST /library-branches/
Update a Branch: PUT /library-branches/{id}/
Delete a Branch: DELETE /library-branches/{id}/
Borrowing Records
Borrow a Book: POST /books/{id}/borrow/
Return a Book: POST /books/{id}/return/
List Borrowing Records: GET /borrowing-records/
Retrieve Borrowing Record Details: GET /borrowing-records/{id}/
Fines
List Fines: GET /fines/
Pay a Fine: POST /fines/{id}/pay/
Retrieve Fine Details: GET /fines/{id}/
Analytics
Most Borrowed Books: GET /analytics/most-borrowed-books/
Active Users: GET /analytics/active-users/
Overdue Books: GET /analytics/overdue-books/
Fine Statistics: GET /analytics/fine-statistics/
