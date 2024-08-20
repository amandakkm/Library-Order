# Order Management System

This is a simple order management system built with Spring Boot. The system allows users to register orders, view a list of orders, delete orders, and calculate late return fees for books.

## Features

- **Register Orders:** Add new orders to the system.
- **View Orders:** Retrieve a list of all orders.
- **Delete Orders:** Remove an order by its ID.
- **Calculate Late Fees:** Calculate a late fee of R$1 per day for overdue books.

## Technologies Used

- **Java 11**
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database (In-memory)**
- **Maven**

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/order-management-system.git
    cd order-management-system
    ```

2. Build the project using Maven:

    ```bash
    mvn clean install
    ```

3. Run the application:

    ```bash
    mvn spring-boot:run
    ```
