# 🐾 Puma Cypress E2E Testing Project

Welcome to the **Puma Cypress End-to-End (E2E) Testing Project** repository! This project is focused on automating the testing process for the Puma e-commerce platform using Cypress to ensure a seamless and reliable user experience.



## 🚀 Project Overview

This project implements the Page Object Model (POM) design pattern to organize test scripts and maximize reusability, readability, and maintainability. It includes:
- **Data-driven testing** with fixtures.
- **Modular design** using page actions and page elements.
- Comprehensive test coverage for key user flows such as product search, cart management, and checkout.



## 📂 Folder Structure
# 🐾 Puma Cypress E2E Testing Project

Welcome to the **Puma Cypress End-to-End (E2E) Testing Project** repository! This project focuses on automating the testing process for the Puma e-commerce platform using Cypress, ensuring a reliable and user-friendly shopping experience.

Here’s an overview of the folder structure :
### Root Directory
```plaintext
├── cypress/               # Contains all Cypress-related files and folders
├── node_modules/          # Project dependencies (installed via npm)
├── README.md              # Project documentation
├── cypress.config.js      # Cypress configuration file
├── package-lock.json      # Automatically generated dependency lock file
├── package.json           # Project metadata and dependencies


###Inside cypress/ Directory
```plaintext
cypress/
├── e2e/                    # Contains test scripts
│   ├── VerifyAllLinks.cy.js
│   └── orderProduct.cy.js
├── fixtures/               # Test data files for data-driven testing
│   ├── CheckoutData.json
│   ├── LoginData.json
│   ├── ProductData.json
│   └── SearchData.json
├── pages/                  # Page Object Model implementation
│   ├── page_actions/       # Contains all reusable actions for pages
│   │   ├── CartPageAction.cy.js
│   │   ├── CheckoutPageAction.cy.js
│   │   ├── HomePageAction.cy.js
│   │   ├── LoginPageAction.cy.js
│   │   ├── LogoutPageAction.cy.js
│   │   └── ProductPageAction.cy.js
│   └── page_elements/      # Stores selectors and page-specific elements
│       ├── CartPageElements.json
│       ├── CheckoutElements.json
│       ├── HomePageElements.json
│       ├── LoginPageElements.json
│       ├── ProductPageElements.json
│       └── RegistrationPageElements.json
├── support/                # Support utilities for custom commands
│   └── commands.js
├── cypress.config.js       # Cypress configuration file
