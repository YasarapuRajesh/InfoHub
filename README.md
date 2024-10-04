# InfoHub

**InfoHub** is a dynamic web application that allows users to register, log in, and manage their personal information. The backend is powered by J2EE Servlets, while user data is stored and managed in a database. After logging in, users can view, edit, and delete their details from the database.

## Features

- **User Registration**: Allows new users to sign up by providing their details.
- **Login**: Registered users can log in with their credentials.
- **User Dashboard**: Displays the user’s stored information after login.
- **Edit/Delete Functionality**: Users can modify or delete their details from the database.
  
## Technologies Used

- **Frontend**:
  - HTML/CSS: User interface design.
  - JavaScript: Client-side interactions for a dynamic experience.
  
- **Backend**:
  - **J2EE Servlets**: Manages the business logic and handles HTTP requests and responses.
  - **Java**: The core language used for the backend logic.
  
- **Database**: Stores user details securely. Make sure to set up the database as per the provided SQL schema.

## How to Run the Application

### 1. Prerequisites

- Ensure you have the following installed:
  - Java Development Kit (JDK)
  - Apache Tomcat (or any compatible servlet container)
  - MySQL or any other compatible database.

### 2. Clone the repository

```bash
git clone https://github.com/your-username/infohub.git
cd infohub

### 3. Set Up the Database

- Import the provided SQL file (if available) into your MySQL database to create the required tables.
- Update the database connection details (URL, username, password) in the servlet configuration.

### 4. Deploy the Application

- Compile the code using your preferred IDE (e.g., Eclipse or IntelliJ IDEA), ensuring that the servlet API is included in the project’s build path.
- Deploy to a Servlet Container:
- If using Apache Tomcat, move the generated WAR file to the webapps directory of Tomcat.
- Alternatively, you can directly run the application from your IDE if it supports servlet deployment.
- Access the Application: Open a browser and go to http://localhost:8080/infohub (or the relevant URL where your Tomcat server is running).

### 5. Running the Application

**Register:** Sign up by providing your details.
**Login:** Log in using your credentials.
**Manage Details:** After login, view, edit, or delete your profile information.

### 6. Folder Structure

**src/:** Contains the HTML, CSS, and JavaScript files for the frontend.
**src/main/java:** Contains the Java files for the J2EE Servlets.
**build/:** Compiled files for deployment.
**.settings/:** Configuration files for the project.

### 7. Future Enhancements

- Add encryption to store passwords securely (e.g., using bcrypt).
- Implement role-based access controls.
- Improve UI with responsive design.
- Add validation for form inputs for better error handling.
