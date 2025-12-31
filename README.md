# 👟 FootwearHub – QA

FootwearHub – QA is a production-style QA automation project created after the completion of the FootwearHub application development.
This repository demonstrates real-world QA practices using Selenium, Cucumber (BDD), Maven, and Allure Reporting.

---

✨ Highlights

* 🧪 Production-ready QA Automation Framework
* 📘 BDD with Cucumber (business-readable scenarios)
* 🧱 Page Object Model (POM) design
* 🔄 End-to-End (E2E) user journey validation
* 📊 Allure Reporting
* ⚙️ Maven-based scalable framework
* ✅ All scenarios executed & passed
* 🖥️ Application Under Test (AUT)

---

## Domain : E-commerce

* Type: Footwear Retail
* Deployment: Netlify
* Environment: QA

- [LIVE URL](https://footwearhub.netlify.app/)

---

## 🧪 QA Scope

* Functional Testing
* UI Navigation Validation
* Smoke Testing
* End-to-End (E2E) Testing
* User Journey Verification
* Automation Framework Design
* Status: ✅ Testing Completed
* Result: All planned scenarios passed

---

## ⚙️ Tech Stack

* Language: Java 11
* Automation: Selenium WebDriver
* BDD: Cucumber
* Build Tool: Maven
* Test Runner: TestNG
* Reporting: Allure
* Design Pattern: Page Object Model (POM)
* IDE: Eclipse
* OS: Windows 11

---

## 📂 Project Structure

``` 

FootwearQA/
│
├── src/test/java
│   ├── pages/              # Page Object classes
│   ├── stepDefinition/     # Cucumber step definitions
│   ├── runner/             # Test runners
│   └── utility/            # Common utilities
│
├── src/test/resources
│   └── features/           # Gherkin feature files
│
├── allure-results/         # Raw execution data
├── allure-report/          # Generated HTML report
│
├── pom.xml                 # Maven configuration
└── README.md               # QA 

```

---


## 🌱 Environments

| Environment  | Name                  |
| ------------ | --------------------- |
| Development  | **FootwearHub – Dev** |
| QA / Testing | **FootwearHub – QA**  |
| Production   | **FootwearHub**       |


---

## 🧾 Implemented Test Scenarios

* General User Navigation
Login Page Access
* New User Registration
Logged-In User Product View
* Add Product to Cart
Complete End-to-End Purchase Journey Execution Summary

* Total Scenarios: 5+
* Total Test Case: 25+
* Execution Time: ~3 minutes
* Browser: Chrome
* Platform: Windows (amd64)
* Status: 🟢 PASSED

---

## 📈 Reporting (Allure)

* This project uses Allure for rich reporting:
* Step-by-step execution
* Scenario grouping
* Execution duration
* Environment details

* Generate report:
  
```

allure serve allure-results

```

---

## 🚀 How to Run Tests

1. Clone the repository
2. Import as a Maven Project
3. Ensure Java 11 is installed
4. Run the Cucumber Runner class
5. View results in console & Allure report

---

## 🎯 QA Objectives Achieved

* Validated core user journeys
Ensured navigation stability
* Verified authentication & product flows
* Built scalable automation framework
* Created production-style QA documentation

---

👤 Author

Swarnavo Pramanik
QA | SDET | Automation Engineer
- [GITHUB](https://github.com/swarnavopramanik)

---

📄 License

This project is created for learning, testing, and portfolio purposes.
Feel free to fork, test, and experiment 🚀

---

> **FootwearHub - QA** => Tested Like Production. Built for Real-World QA Experience. 👟🧪

