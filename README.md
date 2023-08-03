 Horse Lessons - Equestrian Learning Platform
Horse Lessons is an interactive web application designed to connect horse enthusiasts with a variety of horse riding lessons. Whether you are a beginner seeking to learn the basics of horse riding or an experienced rider looking for advanced training, this platform offers lessons for all skill levels. Users can easily browse through the available lessons, enroll in their preferred courses, and manage their profiles.

Table of Contents
Features
Installation
Usage
Database Schema
Technologies Used
Contributing
License
Features
User registration and login system
Browse and search for horse riding lessons
Enroll in lessons based on skill levels
User profile management
Secure password hashing and authentication
Error handling for invalid data and requests
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/horse-lessons.git
Change into the project directory:

bash
Copy code
cd horse-lessons
Install the required dependencies:

Copy code
npm install
Set up the database with PostgreSQL and create the necessary tables. You can use the provided SQL file create_tables.sql to create the tables.

Configure the database connection in the config.js file with your PostgreSQL credentials.

Usage
Run the application:

sql
Copy code
npm start
Access the application in your web browser at http://localhost:8080.

Register for an account or log in if you already have one.

Browse the available lessons, filter by skill level, and click on a lesson to view more details.

Enroll in your preferred lessons and manage your enrolled courses in your profile.

Database Schema
The database schema consists of three main tables:

User: Contains information about registered users, including username, email, password (hashed), first name, last name, home address, city/town, state, and zip code.

Lesson: Stores details about various horse riding lessons, such as title, description, level (beginner, intermediate, advanced), and an image URL for the lesson image.

UserLesson: Facilitates the many-to-many relationship between users and lessons, recording when users enroll in specific lessons.

Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: PostgreSQL
Password Hashing: bcrypt
Fetch API for making API requests
Webpack for bundling and asset management
Contributing
We welcome contributions from the community to improve the platform's functionality, user experience, and security. If you encounter any bugs or have ideas for enhancements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for both commercial and non-commercial purposes.
