# Studex
A Spring Boot web application for managing students, built with Java, Thymeleaf, Spring JPA, and H2 database. The application allows users to create, update, view, and delete student records with a responsive Bootstrap-based UI. 


## 📌 Project Overview
You are responsible for building part of the backend (viewing and deleting student records) and designing the main student list page on the frontend using Thymeleaf and Bootstrap.


## Features
1. Add new students with first name, last name, and email
2. View a list of all students in a tabular format
3. Update student details
4. Delete student records
5. User-friendly Bootstrap-based UI
6.Uses H2 in-memory database for easy setup

## Technologies Used
1. Java (Spring Boot)
2. Spring Web & Spring Data JPA
3. Thymeleaf (for dynamic HTML rendering)
4. H2 Database (in-memory database for quick prototyping)
5. Bootstrap 5 (for styling and responsive UI)


## Installation & Setup
 Prerequisites
 
1. JDK 17+
2. Maven
3. Git
---

## 🔧 Backend Responsibilities

- Create the `Student` entity with fields: `id`, `name`, `email`, `course`.
- Implement `StudentRepository` using Spring Data JPA.
- Implement controller methods in `StudentController`:
  - `@GetMapping("/")` – List all students.
  - `@GetMapping("/delete/{id}")` – Delete a student by ID.

---

## 🎨 Frontend Responsibilities

- Create `students.html` using Thymeleaf.
  - Display all students in a Bootstrap-styled table.
  - Include “Edit” and “Delete” buttons for each row.
- Ensure the Delete button links to `/delete/{id}`.

---


