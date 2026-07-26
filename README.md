#  DSAlgo_TestNG - Selenium Test Automation Framework

A robust Selenium WebDriver automation framework built using **Java, TestNG, Maven, and Page Object Model (POM)** for testing the **DSAlgo (Data Structures & Algorithms)** web application.

The framework supports **cross-browser execution**, **parallel execution**, **data-driven testing**, and **HTML reporting**, making it suitable for enterprise-level UI automation.

## Project Overview

This project automates end-to-end testing of the DSAlgo web application by validating user workflows, navigation, authentication, and data structure modules.

The framework is designed using industry-standard automation practices including:

- Page Object Model (POM)
- TestNG
- Maven
- Selenium WebDriver
- Cross-browser testing
- Parallel execution
- Retry Analyzer
- HTML Reports
- Logging

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Java | Programming Language |
| Selenium WebDriver | UI Automation |
| TestNG | Test Execution Framework |
| Maven | Build Management |
| Page Object Model | Design Pattern |
| Log4j | Logging |
| Extent/HTML Reports | Reporting |
| Git | Version Control |

## Project Structure
```
DSAlgo_TestNG
│
├── src
│   ├── test
│   │   ├── java
│   │   │   ├── pages
│   │   │   ├── stepdefinitions
│   │   │   ├── utilities
│   │   │   ├── runners
│   │   │   └── tests
│   │   └── resources
│
├── reports
├── logs
├── test-output
├── target
│
├── pom.xml
├── testng.xml
├── testng_parallel.xml
├── testngSeq.xml
└── testngCrossBrowserParallel.xml
```

## Features
- Selenium WebDriver Automation
- TestNG Framework
- Page Object Model (POM)
- Maven Project
- Cross Browser Testing
- Parallel Execution
- Sequential Execution
- Retry Failed Test Cases
- HTML Reports
- Log Generation
- Reusable Utility Methods
- Centralized Configuration
- Easy Test Suite Management

##  Automated Modules

### Authentication

- User Registration
- Login
- Logout
- Invalid Login Validation

### Home Page

- Landing Page Validation
- Navigation
- Menu Verification

### Data Structures

- Arrays
- Linked Lists
- Stack
- Queue
- Tree
- Graph

### Practice Questions

- Execute Code
- Validate Output
- Verify Error Messages


## Framework Design

```
TestNG
        │
        ▼
Test Classes
        │
        ▼
Page Object Model
        │
        ▼
Utility Classes
        │
        ▼
Selenium WebDriver
        │
        ▼
Browser
```

## Running Individual Suites

### Sequential Execution

```bash
testngSeq.xml
```

### Parallel Execution

```bash
testng_parallel.xml
```

### Cross Browser Parallel Execution

```bash
testngCrossBrowserParallel.xml
```

---

## Reports

After execution reports are generated under:

```
test-output/
reports/
```

Reports include:

- Test Summary
- Pass/Fail Status
- Execution Time
- Failed Screenshots (if configured)

---

## Logging

Execution logs are generated under:

```
logs/
```

Logs help debug failures and monitor execution.

---

## Framework Highlights
- Modular Page Object Model
- Reusable Components
- Maintainable Codebase
- Maven Dependency Management
- Parallel Test Execution
- Cross Browser Support
- Retry Analyzer for Failed Tests
- Scalable Test Architecture
---
**Skills**
- Selenium WebDriver
- Java
- TestNG
- Maven
- Page Object Model
- Git
- CI/CD
