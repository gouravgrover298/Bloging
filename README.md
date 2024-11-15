# Bloging
blogging-site/

├── src/

│   ├── main/

│   │   ├── java/

│   │   │   └── com/

│   │   │       └── example/

│   │   │           └── blogging/

│   │   │               ├── BloggingApplication.java

│   │   │               ├── controller/

│   │   │               │   └── BlogController.java

│   │   │               ├── model/

│   │   │               │   └── Blog.java

│   │   │               ├── repository/

│   │   │               │   └── BlogRepository.java

│   │   │               ├── service/

│   │   │               │   └── BlogService.java

│   │   │               └── security/

│   │   │                   └── WebSecurityConfig.java

│   │   └── resources/

│   │       ├── application.properties

│   │       └── templates/

│   │           ├── login.html

│   │           ├── dashboard.html

│   │           └── report.html

└── pom.xml

Login Page: Implement a login page where users can enter their username and password. Use Spring Security for authentication.

Dashboard: After successful login, redirect users to a dashboard. Here, users can create, edit, and delete their blogs. The dashboard should display options for managing blog posts.

Blog Structure: Each blog post should have:

Blog Name: A title for the blog post.
Blog Field: A text area for the content of the blog post.
Database Storage: Use Hibernate to map the blog details to a database. Create an entity class for the blog with fields for the blog name and content. Use a SQL database to store the blog details.

Report Page: Create a report page that analyzes the blogs created by the user. This page should:

Showcase the top 5 frequently used words across all blogs created by that user.
Implement a method to extract and count word frequency from the blog content.
Technology Stack
Java: The primary programming language for backend development.
Spring Boot: For building the RESTful API and handling the application logic.
Hibernate: For ORM (Object-Relational Mapping) to interact with the SQL database.
SQL Database: To store user and blog information.
