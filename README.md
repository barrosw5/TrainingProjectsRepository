# 🧠 Spring Boot: Software Engineer API

Welcome to the **Spring Boot** project folder.  
This is a functional backend application designed to demonstrate **REST API** architecture, dependency injection, and database persistence using **JPA**.

The application manages a registry of `Software Engineer` entities, allowing users to retrieve and store engineer profiles.

---

## 🚀 Project Features

- **RESTful Endpoints:** Exposes specific URLs to handle HTTP requests (GET, POST).
- **Service Layer Pattern:** Separates business logic (`SoftwareEngineerService`) from the controller.
- **Data Persistence:** Uses **Spring Data JPA** and **Hibernate** to map Java objects to a database.
- **Entity Management:** Manages a `SoftwareEngineer` model with fields for `id`, `name`, and `techStack`.

---

## 🔌 API Endpoints

The application exposes the following endpoints via the `SoftwareEngineerController`:

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/` | Returns a simple "Hello World Spring Boot" verification message. |
| **GET** | `/api/v1/software-engineers` | Retrieves a list of all registered software engineers. |
| **GET** | `/api/v1/software-engineers/{id}` | Retrieves a specific engineer by their ID. |
| **POST** | `/api/v1/software-engineers` | Adds a new software engineer to the database. |

---

## 🛠️ Technologies Used

- **Java**
- **Spring Boot** (Web, Data JPA)
- **PostgreSQL** (Database)
- **Jakarta Persistence API (JPA)**
- **Maven**
- **JUnit 5** (Testing)

---

### 🔸 About the `.vscode` Folder
The `.vscode` folder is **not required** to run this project.  
It simply stores local settings for **Visual Studio Code**, such as build configuration prompts and null analysis options.  
You can safely delete it if you use another IDE (e.g., IntelliJ or Eclipse) or prefer to keep your repo clean.
