# 🛏️ API Automation Testing – Restful Booker API

## 📌 Project Summary
Comprehensive API automation framework using Java + RestAssured + TestNG to validate full CRUD operations on the Restful Booker API.

## 🔧 Tech Stack
- Java 11+
- RestAssured
- TestNG
- JSON Schema Validator
- Maven (build & dependency mgmt)

## 🧪 Features
- Tests for POST, GET, PUT, PATCH, DELETE endpoints
- Status code + response body assertions
- JSON schema validation
- Edge case scenarios
- Test data management
- Clear test logs and assertions

## 🚀 How to Run
1. Clone the repo
2. Import into IntelliJ or Eclipse
3. Run with Maven:
```bash
mvn clean test
```

## 📂 Folder Structure
```
src/test/java
├── api       # Test classes
└── utils     # Helpers (token gen, base config, schema utils)
```
