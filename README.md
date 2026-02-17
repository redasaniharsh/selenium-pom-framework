# Selenium POM Automation Framework

This project is a Selenium WebDriver automation framework built using Java, TestNG, and Maven. It follows the Page Object Model (POM) design pattern to maintain clean structure and reusability.

---

## Features

- Selenium WebDriver 4
- Java 17
- TestNG for test execution
- Maven project structure
- Page Object Model (POM) architecture
- Explicit waits for stable execution
- Positive and negative login test scenarios
- Reusable BaseTest setup

---

## Project Structure

```
src
 └── test
      └── java
           ├── base
           │     └── BaseTest.java
           ├── pages
           │     └── LoginPage.java
           └── tests
                 └── LoginTest.java
```

---

## Test Scenarios

### Valid Login Test
- Enters correct credentials
- Verifies successful login message

### Invalid Login Test
- Enters incorrect credentials
- Verifies error message

---

## How to Run

### From IntelliJ
Right click `LoginTest` and select **Run**.

### From Command Line
```
mvn clean test
```

---

## Technologies Used

- Java
- Selenium WebDriver
- TestNG
- Maven
- Git & GitHub

---

## Author

Harsh Redasani
