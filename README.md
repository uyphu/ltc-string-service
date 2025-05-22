# 🧠 LTC String Service

This is a Spring Boot microservice for solving and testing **LeetCode String category problems**, starting with the "Merge Strings Alternately" challenge.

Part of a larger microservices-based system for practicing and organizing LeetCode solutions by category (e.g., String, Array, Two Pointers, Sliding Window, etc.).

---

## 📌 Features

- ✅ REST API to solve string-based algorithm problems
- ✅ Modular service structure to easily add more problems
- ✅ Example: Merge two strings alternately (`/api/string/merge`)
- ✅ Clean, production-ready Spring Boot setup

---

## 🚀 Getting Started

### Prerequisites

- Java 21+
- Maven
- Git

### Clone and Run

```bash
git clone https://github.com/uyphu/ltc-string-service.git
cd ltc-string-service
./mvnw spring-boot:run
```
The app will start on:
📍 http://localhost:8080

##@ 📬 API Endpoints
🔹 POST /api/string/merge
Merge two strings by alternating characters. If one string is longer, append the remainder.

Request:

```bash
{
  "word1": "abc",
  "word2": "pqr"
}
```
Response:

```bash
{
  "merged": "apbqcr"
}
```

### 📦 Project Structure
```csharp
ltc-string-service/
├── controller/          # REST API controllers
├── dto/                 # Input/Output models
├── service/             # Business logic
├── resources/
│   └── application.yml  # App config
└── LTCStringServiceApplication.java
```
## 🧠 Motivation
This project helps me:

Practice algorithm implementation

Build scalable backend structure

Showcase clean code and RESTful design

## 🧑‍💻 Author
Phu Le
GitHub | LinkedIn