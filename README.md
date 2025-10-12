# 🧩 Test-Driven & Behavior-Driven Development with CI/CD

## 📘 Overview

This project demonstrates **Test-Driven Development (TDD)**, **Behavior-Driven Development (BDD)**, and **Test Automation** integrated with a **CI/CD pipeline** using **Spring Boot**, **JUnit**, **Cucumber**, **Selenium**, and **GitHub Actions**.

---

## ⚙️ Tech Stack

* **Backend:** Spring Boot (Java 17)
* **Testing:** JUnit 5, Mockito, Cucumber, REST Assured, Selenium
* **CI/CD:** GitHub Actions
* **Database:** MySQL
* **Build Tool:** Maven

---

## 🧠 Test-Driven Development (TDD)

**Features:**

* User Signup → validates unique email & username
* User Login → validates credentials and returns responses

**TDD Cycle:**

1. **Red:** Write failing test
2. **Green:** Write minimum code to pass
3. **Refactor:** Clean up while keeping tests green

**Example Tests:**

* `UserControllerUnitTest`
* `UserControllerTest`

---

## 🧩 Behavior-Driven Development (BDD)

**Feature Example (Gherkin):**

```gherkin
Feature: User Login
  Scenario: Successful login with valid credentials
    Given a user exists
    When the user logs in
    Then login should be successful
```

**Tools:**

* Cucumber + JUnit Integration
* Step Definitions written in Java

---

## 🤖 Test Automation & Continuous Integration

**Automated Tests:**

* 2 Selenium UI Tests → Login & Signup
* 2 API Tests → Signup and Login using REST Assured
* Unit tests executed via Maven

**CI/CD Pipeline (GitHub Actions):**

* Builds project using Maven
* Runs all unit and automation tests
* Integrates MySQL service container
* Reports success/failure automatically

✅ **Result:** All tests passed and build marked **SUCCESS**.

---

## 📈 Outcome

* Demonstrated TDD & BDD workflows
* Automated backend + UI + API testing
* Successful CI/CD pipeline run on GitHub
