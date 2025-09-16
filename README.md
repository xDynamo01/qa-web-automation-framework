# QA Web Automation Framework

## Overview
This repository contains a robust and maintainable automation framework built with Selenium WebDriver and Java, designed for regression testing of web applications. It follows the Page Object Model (POM) design pattern and utilizes TestNG for test management and reporting.

## Features
- **Page Object Model Design:** Enhances test maintenance and reduces code duplication.
- **TestNG Integration:** For structuring tests, parameterization, and generating detailed HTML reports.
- **CI/CD Ready:** Includes a GitHub Actions workflow for running tests on push/pull requests.
- **Data-Driven Testing:** Support for external data sources (e.g., JSON, Excel).
- **Cross-Browser Testing:** Configurable to run tests on Chrome, Firefox, etc.

## Tech Stack
- Java
- Selenium WebDriver
- TestNG
- Maven
- GitHub Actions

## Project Structure

qa-web-automation-framework/
├── src/test/java
│ ├── pages/ # Page Object classes
│ ├── tests/ # Test classes
│ └── utilities/ # Helper classes (e.g., WebDriver setup)
├── src/test/resources
│ ├── testdata/ # External test data files
│ └── config.properties # Configuration file
├── pom.xml
└── .github/workflows/ # CI/CD pipeline
