# Book Publication System

The Book Publication System is a web application designed to automate and streamline the processes involved in a book publication business. It provides features for managing authors, books, ratings, and generating reports.

## Features

- Author Registration: Register authors with their first name, last name, email, and contact number.
- Book Registration: Register books with an ISBN number, category, title, and associated author(s).
- Category-Author Relationship: Allow authors to write books in different categories and multiple authors for a category.
- Book Search: Search books using ISBN number.
- Book Rating: Allow users to like books and maintain a like count for each book.
- Data Integrity: Ensure that a book cannot exist without an author.
- Report Generation: Generate periodic reports containing the like count for each author.
- Logging: Generate log entries for each system event.

## Technologies Used

- Backend: Node.js, Express.js
- Frontend: React.js
- Database: MySQL
- Other Libraries: Axios (HTTP client), Bootstrap (CSS framework)

## Setup Instructions

1. Clone the repository: `git clone https://github.com/your-username/book-publication-system.git`
2. Install dependencies:
   - Backend: Navigate to the `backend` directory and run `npm install`
   - Frontend: Navigate to the `frontend` directory and run `npm install`
3. Database Setup:
   - Create a MySQL database.
   - Configure the database connection details in the backend's `.env` file.
   - Run database migrations using `npx sequelize-cli db:migrate` in the backend directory.
4. Start the Application:
   - Backend: Run `npm start` in the backend directory.
   - Frontend: Run `npm start` in the frontend directory.
5. Access the application in your web browser at `http://localhost:3000`.

## Folder Structure

- `backend`: Contains the backend code and API endpoints.
- `frontend`: Contains the frontend code and React components.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

[backend_cba.git](https://github.com/BhagyaAriyadasa/backend_cba.git)

