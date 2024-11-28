# Tendable Selenium Automation Project

## Overview
This project automates tests for key functionalities on the Tendable website. The tests include:
1. Verifying the accessibility of top-level menus: Home, Our Story, Our Solution, Why Tendable.
2. Checking the presence and functionality of the "Request a Demo" button on these menu pages.
3. Testing the "Contact Us" form for validation errors when the "Message" field is left empty.
4. Generating a bug report if validation fails.

## Requirements
- Java 8 or later
- Maven
- ChromeDriver (compatible with your Chrome version)

## How to Run
1. Clone the repository: `git clone <repository_url>`
2. Open the project in your favorite IDE (e.g., IntelliJ, Eclipse).
3. Ensure dependencies are resolved (`mvn clean install`).
4. Run the `TendableTest.java` file.

## Strategy
- **Robust Locators**: Used XPath locators to identify elements reliably.
- **Scalability**: The tests are modular to allow future expansion.
- **Bug Reporting**: Integrated Apache POI for generating detailed bug reports in Word format.
