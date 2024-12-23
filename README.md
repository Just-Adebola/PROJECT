E-Library API System

The E-Library API System is a robust online platform designed to simplify library management. This intuitive API enables users to effortlessly borrow and return books, manage their account information, and track book availability in real-time.
Key Features:

1. Comprehensive user management: Create, read, update, and delete (CRUD) user accounts.
2. Book management: Perform CRUD operations on book catalog entries.
3. Borrowing system: Authorized users can borrow available books through a dedicated endpoint.

Getting Started:

To utilize the E-Library API System, follow these steps:

1. Create a user account via a POST request. Note that user status defaults to "active."
2. Verify available books and select the desired title.
3. If the book is available, the system will automatically process the borrowing request. Otherwise, it will return an error message with a relevant status code.

To run the code use: uvicorn app.main:app --reload
