
```markdown
# 🪄 Hogwarts Artifacts Online

Hogwarts Artifacts Online is a Spring Boot-based web application that manages magical artifacts at Hogwarts. It provides CRUD functionality for artifacts and wizards, showcasing modern Java backend development practices with a focus on layered architecture, validation, exception handling, and Thymeleaf-based UI.

## 🧰 Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring MVC**
- **Spring Data JPA**
- **Thymeleaf**
- **Hibernate Validator**
- **H2 Database** (in-memory for dev/testing)
- **Bootstrap** (for styling)
- **Lombok** (to reduce boilerplate)
- **Maven** (build tool)

---

## ✨ Features

- Manage magical artifacts and assign them to wizards
- Form-based input with server-side validation
- RESTful controller structure
- Exception handling and error pages
- Relational mapping between entities
- H2 Console for quick data inspection
- Beautiful and responsive UI with Bootstrap

---

## 📁 Project Structure

```

src
├── main
│   ├── java/com/example/hogwarts
│   │   ├── controller
│   │   ├── model
│   │   ├── repository
│   │   ├── service
│   │   ├── exception
│   └── resources
│       ├── templates
│       ├── static
│       ├── application.properties

````

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Maven 3.6+

### Run the Application

```bash
git clone https://github.com/sauravdaruka/hogwarts-artifacts-online.git
cd hogwarts-artifacts-online
mvn spring-boot:run
````

### Access URLs

* Home: `http://localhost:8080`
* H2 Console: `http://localhost:8080/h2-console`
  (JDBC URL: `jdbc:h2:mem:testdb`, User: `sa`, Password: leave blank)


## 🧪 Testing

Basic tests are included to verify controller and service logic. You can run:

```bash
mvn test
```

---

## ✍️ Author

[Saurav Daruka](https://github.com/sauravdaruka)

```
