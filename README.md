
# Novel Nest

Novel Nest is a web application designed to manage novels, authors, genres, and user preferences, providing users with a platform to explore and manage their reading interests effectively.


## Features


- Novel Management: CRUD operations for novels, metadata storage (title, author, genre, etc.), and search/filter functionality.
- Author and Genre Management: Manage author details and classify novels by genre.
- User Profiles: Store user preferences and reading history, including bookmarking.
- Admin Dashboard: Tools for administrators to manage content and moderate user-generated reviews/comments.


## Getting Started
To run Novel Nest locally, follow these steps:

### Prerequisites
- Install XAMPP (https://www.apachefriends.org/index.html) or WAMP (https://www.wampserver.com/en/) to set up a local server environment.

### Installation

1 Clone the repository:
```bash
 git clone https://github.com/Abdul-Wahab-Abbasi/novel_nest.git
```
2 Database Setup:

- Open XAMPP/WAMP and start Apache and MySQL servers.
- Navigate to phpMyAdmin (http://localhost/phpmyadmin) and create a new database named competition.
- Import the included SQL file (database.sql) into your newly created competition database to set up the necessary tables and initial data.
3 Configuration:
- Navigate to the project directory and locate config.php.
- Update the database connection details in config.php to match your local database setup.
4 Run the Application:
- Start your XAMPP/WAMP server if not already running.
- Open a web browser and navigate to http://localhost/novel_nest (replace novel_nest with your project directory name if different).

### Admin Panel Access
- Username: admin@gmail.com
- Password: admin

### User Access
- Username: wahababbasi923@gmail.com
- Password: 12345
### Database Details
- Database Name: competition
## Contribution
Contributions are welcome! Please fork the repository and create a pull request with your improvements.
## License
This project is licensed under the MIT License.

