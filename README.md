# PHP-Based Web Form Submission and Database Integration

## 📌 Project Overview

This project is a PHP-based web application that allows users to submit their information through a signup form and stores the submitted data in a MariaDB database. Nginx is used as the web server to host the application.

The project demonstrates how frontend forms, server-side PHP processing, and database connectivity work together to build a dynamic web application.

## 🎯 Objectives

- Develop a signup form using HTML.
- Process form submissions using PHP.
- Connect PHP with MariaDB using a compatible MySQL database connector.
- Store user information in a database.
- Display a success message after successful form submission.
- Verify stored records using SQL queries.

## 🛠️ Technologies Used

- **HTML** – Structures the signup form.
- **PHP** – Handles form submissions and database operations.
- **MariaDB** – Stores user information.
- **Nginx** – Serves the web application.
- **MySQL-compatible PHP Connector** – Enables PHP-to-MariaDB communication.
- **Linux** – Provides the server environment.
- **SQL** – Retrieves and verifies stored records.

## 📝 Input Fields

The signup form collects the following information:

- Name
- Email
- Website URL
- Comment
- Gender (Female, Male, or Other)

## ⚙️ How It Works

1. The user opens the signup website in a web browser.
2. The user enters the required information into the form.
3. The form submits the data to the PHP backend.
4. PHP processes the submitted information.
5. The database connector enables PHP to communicate with MariaDB.
6. The submitted information is inserted into the `users` table in the `FCT` database.
7. The website displays a success message and the submitted information.
8. The saved records are verified using SQL queries.

## 🗄️ Database Verification

The application uses the `FCT` database and the `users` table.

The following SQL commands were used to verify the stored records:

```sql
USE FCT;

SELECT * FROM users;
```

The table contains the following columns:

| Column | Description |
|---|---|
| `id` | Unique record identifier |
| `name` | User's name |
| `email` | User's email address |
| `website` | User's website URL |
| `comment` | User's comment |
| `gender` | Selected gender |

## 📸 Project Output

### 1. Signup Form

The website provides a form where users can enter their name, email, website, comment, and gender.

### 2. Successful Form Submission

After submitting the form, the website displays the message:

**"New record created successfully!"**

The submitted information is displayed on the result page.

### 3. Database Output

The MariaDB terminal displays the records stored in the `users` table using the `SELECT * FROM users;` query.

These outputs demonstrate successful form submission and database integration.

## 🚀 Key Features

- Simple and user-friendly signup form.
- PHP-based server-side form processing.
- Integration with MariaDB.
- Automatic storage of submitted information.
- Success message after submission.
- SQL-based verification of database records.
- Deployment using the Nginx web server.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Configuring a Linux-based web server environment.
- Working with PHP for server-side programming.
- Connecting PHP applications to MariaDB.
- Creating and querying database tables.
- Handling HTML form submissions.
- Testing web applications and verifying database operations.

## 🔮 Future Enhancements

- Add input validation and error handling.
- Implement duplicate email detection.
- Add functionality to update and delete records.
- Improve the user interface with CSS.
- Configure HTTPS for secure communication.
- Implement secure database queries using prepared statements.

## ✅ Conclusion

This project successfully demonstrates the development of a PHP-based web application integrated with MariaDB and hosted using Nginx. User information submitted through the signup form is processed by PHP, stored in the database, and verified through SQL queries.

The project strengthened my practical understanding of web development, server configuration, database connectivity, and application testing.

---

**Project Category:** Web Development and Database Integration  
**Backend:** PHP  
**Database:** MariaDB  
**Web Server:** Nginx
