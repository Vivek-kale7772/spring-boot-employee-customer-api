# Employee & Customer Management System (CRUD)

A professional Spring Boot REST API application designed to manage internal employees and customer records efficiently. This project demonstrates the implementation of CRUD (Create, Read, Update, Delete) operations using modern Java best practices.

## 🚀 Features
- **Employee Management**: Full lifecycle management of staff records.
- **Customer Tracking**: Maintain and update customer information.
- **RESTful Architecture**: Clean API endpoints for easy integration.
- **Data Persistence**: Integrated with Spring Data JPA for robust database handling.

## 🛠️ Tech Stack
- **Language**: Java 17+
- **Framework**: Spring Boot 3.x
- **Database**: H2 (In-memory) / MySQL support
- **Build Tool**: Maven
- **ORM**: Spring Data JPA / Hibernate

## 📂 Project Structure
- `com.example.crud.model`: Entity definitions for Employee and Customer.
- `com.example.crud.repository`: JPA repositories for database interaction.
- `com.example.crud.service`: Business logic layer.
- `com.example.crud.controller`: REST controllers exposing API endpoints.

## 📡 API Endpoints

### Employees
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/employees` | Get all employees |
| GET | `/api/employees/{id}` | Get employee by ID |
| POST | `/api/employees` | Create new employee |
| PUT | `/api/employees/{id}` | Update existing employee |
| DELETE | `/api/employees/{id}` | Delete an employee |

### Customers
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/customers` | Get all customers |
| GET | `/api/customers/{id}` | Get customer by ID |
| POST | `/api/customers` | Create new customer |
| PUT | `/api/customers/{id}` | Update existing customer |
| DELETE | `/api/customers/{id}` | Delete a customer |

## ⚙️ Setup & Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vivek-kale7772/spring-boot-employee-customer-api.git
   ```
2. **Navigate to project folder**:
   ```bash
   cd "Employee CRUD"
   ```
3. **Build the project**:
   ```bash
   mvn clean install
   ```
4. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

The application will be available at `http://localhost:8080`.

---
*Created by [Vivek](https://github.com/Vivek-kale7772)*
