**Introduction**
This project is a Selenium WebDriver automation framework built with Java, designed for testing web applications. It includes a Page Object Model (POM) structure, supports TestNG, and integrates with Allure Reporting for test results analysis.
**Features**
- Cross-browser testing using Chrome, Firefox, Edge
- Page Object Model (POM) for maintainability
- Data-driven testing using Excel/JSON
- TestNG integration for parallel execution
- CI/CD compatibility with GitHub Actions
- Logging using Log4j
- Reporting with Allure Reports
**Prerequisites**
- Java 17+
- Maven
- TestNG
- Selenium WebDriver
- WebDriverManager
**Installation**
Clone the repository:
git clone https://github.com/AbdElRhman8Magdy/Task_AbdElRhman_Magdy.git
cd selenium-testing-framework


**Install dependencies:**
mvn clean install


**Project Structure**
├── src
│   ├── main/java/com/project/pages
│   ├── test/java/com/project/tests
│   ├── utils/
│   ├── resources/
│   ├── reports/
│   ├── pom.xml
│   ├── README.md


**Usage**
Run tests using Maven:
mvn test


Run specific test cases:
mvn test -Dtest=LoginTest


Generate Allure reports:
mvn allure:serve    


**Configuration**
Modify the config.properties file for:
- Base URL
- Browser settings
- Test credentials
Contributing
Pull requests are welcome! Please follow proper code formatting and commit message conventions.

Would you like me to adjust it based on specific test cases or framework configurations? 🚀
