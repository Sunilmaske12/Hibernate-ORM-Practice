# Hibernate ORM Practice

A collection of Java Hibernate ORM practice projects developed during my Java Development course at Anudip.

This repository contains hands-on examples demonstrating Hibernate configuration, database operations, entity relationships, mapping techniques, and query execution using MySQL.

## Projects Included

The repository contains multiple independent Maven projects covering different Hibernate concepts.

### 1. Basic Hibernate
- Hibernate configuration
- XML-based entity mapping
- Saving entity objects to the database

### 2. One-to-One Mapping
- Mapping relationships between two entities
- User and Address entity examples

### 3. Annotation-Based Mapping
- Entity mapping using Hibernate annotations
- Car entity example

### 4. Hibernate CRUD Operations
- Insert records
- Retrieve records
- Update records
- Delete records

### 5. One-to-Many Mapping
- Department and Employee relationship
- Entity relationship configuration

### 6. Advanced Hibernate Examples
- XML-based mapping
- Embedded objects
- One-to-One relationship
- One-to-Many relationship
- Many-to-Many relationship
- Cascading operations
- Hibernate Query Language (HQL)
- Criteria API
- Native SQL queries
- Pagination
- Entity lifecycle states
- Data fetching

## Technologies Used

- Java
- Hibernate ORM
- MySQL
- Maven
- XML Configuration
- Hibernate Annotations
- Eclipse IDE

## Project Structure

```text
Hibernate/
│
├── Anudip_Hibernate/
├── Anudip_Hibernate_1to1mapping/
├── Anudip_Hibernate_Car_Annotation/
├── Anudip_Hibernate_Crud/
├── Anudip_Hibernate_one-many_mapping2/
│
└── Hibarnate/
    └── src/
        └── main/
            └── java/
                ├── com/
                ├── XMLMapping/
                ├── cascading/
                ├── criteriaAPI/
                ├── embaddingObjects/
                ├── hibernateQueryLanguage_HQL/
                ├── manyToManyMapping/
                ├── oneToManyMapping/
                └── oneToOneMapping/
```

## Getting Started

### Prerequisites

- JDK
- Apache Maven
- MySQL Server
- Eclipse IDE or another Java IDE

### Database Configuration

1. Create the required MySQL database for the selected project.
2. Open its `hibernate.cfg.xml` or corresponding Hibernate configuration XML file.
3. Configure the database URL, username, and password for your local environment.
4. Ensure the required database and tables are available.

### Running the Projects

Each folder represents an independent Maven project.

1. Clone the repository:

   ```bash
   git clone https://github.com/Sunilmaske12/Hibernate-ORM-Practice.git
   ```

2. Import the required project folder into Eclipse as an existing Maven project.

3. Update the MySQL connection configuration.

4. Resolve Maven dependencies.

5. Run the appropriate Java main class.

## Learning Objectives

- Understand Hibernate ORM fundamentals.
- Perform database CRUD operations.
- Implement entity relationships.
- Work with XML and annotation-based mappings.
- Write HQL, Criteria API, and native SQL queries.
- Understand cascading and entity lifecycle states.
- Practice database persistence using Java and Hibernate.

## Author

**Sunil Maske**

- GitHub: https://github.com/Sunilmaske12
- LinkedIn: https://www.linkedin.com/in/sunil-maske/
- LeetCode: https://leetcode.com/u/maskesunil16/
