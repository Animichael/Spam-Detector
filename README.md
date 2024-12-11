
**Spam Email Detection System using Logistic Regression**


**Overview**
This project focuses on the development and deployment of a Spam Email Detection System using Logistic Regression. The system classifies incoming emails into spam and non-spam categories. For the case study, the Jumia platform was used to simulate the spam detection process, but this system can be adapted to any platform that requires spam email filtering.

**Features**
Logistic Regression Model: The core model is built using Logistic Regression to predict whether an email is spam or not.
Flask Web Application: The model is deployed in a Flask web application, offering a user-friendly interface for interacting with the spam detection system.
User Authentication: Includes login and logout functionalities, ensuring secure access to the system.
Dashboard: A dashboard that displays the filtered spam and non-spam emails.
Database Integration: The system stores emails in separate tables for spam and non-spam emails in a database, ensuring efficient data management.
Modal Display: After classification, both spam and non-spam emails are displayed in modals for easy viewing.
Delete Functionality: Users can delete any email records directly from the dashboard.
Technologies Used
Machine Learning: Logistic Regression for spam email classification.
Backend: Flask for serving the web application and handling user requests.
Database: Used for storing emails in separate tables for spam and non-spam.
Frontend: HTML, CSS, and JavaScript for the user interface.
Authentication: Simple user login and logout functionalities for secure access.

**How It Works**
Login: Users can log in to access the system.
Email Classification: When an email is uploaded, the system uses the trained logistic regression model to predict if the email is spam or non-spam.
Database Storage: The emails are stored in the database, with spam emails going into a dedicated spam table and non-spam emails into a separate table.
Display: The filtered emails are shown in a dashboard, and users can view them in modals.
Delete: Users can delete specific emails from the database directly from the dashboard.

