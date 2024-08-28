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


API Endpoints
Authentication
POST /api/token/ - Obtain authentication token
User Endpoints
GET /api/users/ - List users
POST /api/users/ - Create a user
GET /api/users/{id}/ - Retrieve a user
PUT /api/users/{id}/ - Update a user
DELETE /api/users/{id}/ - Delete a user
Book Endpoints
GET /api/books/ - List books
POST /api/books/ - Create a book
GET /api/books/{id}/ - Retrieve a book
PUT /api/books/{id}/ - Update a book
DELETE /api/books/{id}/ - Delete a book
Author Endpoints
GET /api/authors/ - List authors
POST /api/authors/ - Create an author
GET /api/authors/{id}/ - Retrieve an author
PUT /api/authors/{id}/ - Update an author
DELETE /api/authors/{id}/ - Delete an author
Library Branch Endpoints
GET /api/library-branches/ - List library branches
POST /api/library-branches/ - Create a library branch
GET /api/library-branches/{id}/ - Retrieve a library branch
PUT /api/library-branches/{id}/ - Update a library branch
DELETE /api/library-branches/{id}/ - Delete a library branch
Borrowing Record Endpoints
POST /api/borrowing-records/borrow_book/ - Borrow a book
POST /api/borrowing-records/return_book/ - Return a book
GET /api/borrowing-records/ - List borrowing records
GET /api/borrowing-records/{id}/ - Retrieve a borrowing record
Fine Endpoints
GET /api/fines/ - List fines
POST /api/fines/pay_fine/ - Pay a fine
GET /api/fines/{id}/ - Retrieve a fine
Analytics Endpoints
GET /api/fines/analytics/ - Retrieve analytics

