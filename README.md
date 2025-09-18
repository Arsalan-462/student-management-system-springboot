# Student Management System  

A full-stack **Student Management System** built with **Spring Boot** (Backend) and **HTML, CSS, Bootstrap** (Frontend).  
This application provides an interface for managing student records and performing **CRUD operations** (Create, Read, Update, Delete) efficiently.  

---

## Features  

### Backend – Spring Boot & REST APIs  
- Developed robust and modular backend using **Spring Boot**.  
- Exposed **RESTful APIs** for student management:  
  - Create new student records  
  - Update existing student details  
  - Retrieve student information (single or list)  
  - Delete student records  
- Layered architecture with **Controllers, Services, and Repositories**.  
- Database integration using **Spring Data JPA**.  
- JSON-based communication for easy frontend integration.  

### Frontend – HTML, CSS & Bootstrap  
- Responsive UI built with **HTML5, CSS3, and Bootstrap 5**.  
- Dynamic **forms** for adding and editing student details.  
- **Data tables** for listing students with actions (Edit/Delete).  
- Bootstrap elements (cards, modals, navbars, alerts) for clean UI/UX.  
- Input validation and **feedback messages** for reliable form submissions.  

---

## Tech Stack  

- **Backend:** Java, Spring Boot, Spring Data JPA, REST APIs, MySQL/PostgreSQL  
- **Frontend:** HTML5, CSS3, Bootstrap 5  
- **Tools:** Postman (API testing), Maven  

---
student-management-system/

│── backend/ # Spring Boot backend

│ └── src/main/java/...

│── frontend/ # HTML, CSS, Bootstrap frontend

│── README.md # Documentation

---

## Getting Started  

### Backend Setup  

1. Navigate to the backend folder:  
cd backend
2. Configure the database in `src/main/resources/application.properties`:  
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
3. Run the Spring Boot project:  
mvn spring-boot:run
4. Backend will be available on:  
http://localhost:8080

### Frontend Setup  

1. Navigate to the frontend folder:  

2. Open `index.html` in a browser.  
- Ensure API endpoint URLs inside forms or script files point to your backend (`http://localhost:8080/api/students`).  

---

## Example API Endpoints  

- **Get All Students:** `GET /api/students`  
- **Get Student by ID:** `GET /api/students/{id}`  
- **Add New Student:** `POST /api/students`  
- **Update Student:** `PUT /api/students/{id}`  
- **Delete Student:** `DELETE /api/students/{id}`  

---

## Future Enhancements  

- Add authentication & role-based access (Admin/Student).  
- Support file uploads for student documents.  
- Pagination and search functionality in student list view.  
- React or Angular frontend for richer interactivity.  

---

## Author  

**Mohammad Arsalan**  
📧 [md.arsalan462@gmail.com](mailto:md.arsalan462@gmail.com)  


