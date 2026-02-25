**How can you run this project on your computer buy following bellow steps**

🎓 Student Management System
A full-stack "Student Management System" built with:

* ⚙️ Spring Boot (Backend)
* 🗄️ MySQL (Database)
* 🎨 React (Frontend)

📸 Features
✅ Add Student
✅ View Students
✅ Update Student
✅ Delete Student
✅ Modern UI

🧩 Tech Stack

## Backend
* Java
* Spring Boot
* Spring Data JPA
* MySQL

## Frontend
* React
* Axios
* Bootstrap / CSS

⚙️ Prerequisites
Make sure you have installed:
✅ Java JDK 17+
✅ Maven (or use mvnw included)
✅ Node.js (v16+ recommended)
✅ MySQL

🗄️ Database Setup
Open MySQL and run: CREATE DATABASE student_management_system;

🔧 Backend Setup

1️⃣ Go to server folder
cd server

2️⃣ Configure database
Open: src/main/resources/application.properties
Update with your MySQL credentials properties:

spring.datasource.url=jdbc:mysql://localhost:3306/student_management_system
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=8080

3️⃣ Run backend
mvn spring-boot:run
Backend will run at: http://localhost:8080

🎨 Frontend Setup
1️⃣ Go to frontend folder: cd frontend

2️⃣ Install dependencies: npm install

3️⃣ Start frontend: npm start
    Frontend runs at: http://localhost:3000

🚀 How to Use

1️⃣ Start MySQL
2️⃣ Run Backend
3️⃣ Run Frontend
4️⃣ Open browser → http://localhost:3000

📂 Project Structure
student-management-system
 ├── server (Spring Boot)
 └── frontend (React)

🤝 Contributing
Pull requests are welcome.
For major changes, please open an issue first.

📜 License
This project is for learning purposes.

👨‍💻 Author
Mohamud Sk

---
