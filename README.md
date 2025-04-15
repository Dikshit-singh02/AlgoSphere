:

🔐 AdminSphere - Admin Panel Management System
AdminSphere is a robust and secure Admin Panel web application built using Java Servlets (with Ant), JSP, JPA, and Enterprise Java Beans (EJB). This project provides a centralized interface for administrators to manage users effectively, ensuring seamless data handling and secure access through RESTful web services.

🚀 Features
🔐 Admin Login with Session Management

🧾 User Registration (First Name, Last Name, Age, Gender, Username, Password)

🔄 Update, Delete, and Search Users

📁 JPA Integration for persistent data storage

🧠 EJB Implementation with Bean Validation

🔗 One-to-One Entity Relationship Mapping

🌐 Secure RESTful Web Services for accessing and managing employee data

🎨 CSS-styled UI for improved user experience

🧩 Tech Stack
Java Servlets (Ant Build)

JSP & HTML

CSS

JPA with EntityManager

EJB (Enterprise Java Beans)

RESTful Web Services (Java & Node.js)

NetBeans IDE

MySQL Database

📁 Project Structure
pgsql
Copy
Edit
AdminSphere/
│
├── src/
│   ├── config/
│   ├── model/
│   ├── dao/
│   ├── servlets/
│   └── ejb/
│
├── WebContent/
│   ├── jsp/
│   ├── css/
│   └── index.jsp
│
├── build.xml
└── README.md
📚 How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/AdminSphere.git
Open in NetBeans and build using Ant.

Configure the database in persistence.xml.

Deploy on your local server (e.g., Apache Tomcat or GlassFish).

Access the app via http://localhost:8080/AdminSphere.

