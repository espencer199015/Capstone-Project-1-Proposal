Capstone Project 1 Proposal
Step Two of your first capstone is all about fleshing out your project idea. For this step, please write a proposal based on the project idea you agreed on with your mentor. This proposal should be a 1-2 page document that answers the following questions: 
Project Proposal

1. Goal of the Website:
The goal of our website, "Horse Lessons," is to provide an interactive platform where users can access and enroll in various horse riding lessons based on their skill levels, ranging from beginner to advanced. The website aims to create a community for horse enthusiasts and learners, facilitating the discovery and booking of horse riding lessons.

2. Target Users:
The primary users of the website will be individuals interested in horse riding lessons. The demographic will include people of all ages and backgrounds who have an interest in equestrian activities. Whether they are complete beginners looking to start horse riding or experienced riders seeking advanced training, the platform will cater to a diverse audience of horse enthusiasts.

3. Data Usage:
The website will utilize data related to users, lessons, and the user-lesson enrollment relationship. For user data, we will collect information such as username, email, hashed passwords, first name, last name, home address, city/town, state, and zip code. Lesson data will include details like lesson title, description, level (beginner, intermediate, advanced), and an image URL for the lesson image. Additionally, we will store data in the UserLesson table, which will record the date when a user enrolls in a particular lesson.

4. Project Approach:
a. Database Schema:
The database will consist of four main tables: User, Lesson, UserTransaction and Transactions. The User table will store information about registered users, while the Lesson table will hold details about various horse riding lessons. The UserLesson table will facilitate the many-to-many relationship between users and lessons, recording when users enroll in specific lessons. The transactions table will store information on user transaction histories.
Database Schema

b. API Issues:
While selecting or building the API, we may face issues related to data validation, error handling, and data consistency. Ensuring that the API returns proper error messages and handles invalid requests will be crucial for a smooth user experience.

c. Security Measures:
The website will incorporate security measures to protect sensitive user information, such as hashed passwords and personal data. User authentication and authorization will be implemented to ensure that only authorized users can access certain functionalities.

d. Functionality:
Key functionalities of the website will include user registration and login, lesson browsing and enrollment, and user profile management. Users will be able to search for lessons based on skill levels and view detailed information about each lesson before enrolling.

e. User Flow:

New visitors can register for an account or log in if they already have one.
Upon registration or login, users will be directed to the homepage showcasing featured lessons.
Users can search for specific lessons or filter lessons based on skill levels.
Clicking on a lesson will display more information about it, including a description and the option to enroll.
Users can access their profile page to view their enrolled lessons and update their personal details.
On successful enrollment, users will receive confirmation and relevant details about the lesson.
In conclusion, "Horse Lessons" aims to be a user-friendly platform that connects horse enthusiasts with professional horse riding lessons. By providing a seamless user experience, robust data management, and strong security features, we seek to create a valuable resource for both learners and instructors in the equestrian community.