# UI Automation Framework (Selenium + Java)

A robust, maintainable UI test automation framework built using **Selenium WebDriver**, **Java**, **TestNG**, **Maven**, and **Page Object Model (POM + Page Factory)**. Designed for functional UI testing with clear structure, reporting, and CI/CD support.

---

## 🔧 Tech Stack

- Java 11+
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model + Page Factory
- Extent Reports
- Jenkins-ready

---

## 📁 Project Structure

src/
└── test/
├── base/               → WebDriver initialization & test base
├── pages/              → Page classes using PageFactory
├── tests/              → Test cases grouped by functionality
├── utils/              → Utility methods (waits, config, screenshots)
└── resources/
└── config.properties  → Environment configs (browser, URL, timeouts)

---

## ✅ Key Features

- Page Object Model with PageFactory for maintainability
- Cross-browser execution supported
- Extent Reports for visual HTML reports
- Screenshot capture on failure
- Parameterized execution via TestNG XML
- CI/CD ready (Jenkins/GitHub Actions)

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/tushargaur28/UIAutomationFramework.git
cd UIAutomationFramework

2. Run All Tests

mvn clean test

3. Run Specific Suite

mvn clean test -DsuiteXmlFile=testng-smoke.xml



⸻

📊 Reports & Screenshots
	•	HTML Report → test-output/ExtentReports/index.html
	•	Screenshots (on failure) → /screenshots

⸻

🔄 CI/CD Integration

Use in any pipeline:

mvn clean test

Make sure to archive:
	•	/test-output
	•	/logs
	•	/screenshots

⸻

👤 Author

Tushar Gaur
📧 gaur.tushar281@gmail.com
🔗 LinkedIn

⸻

📄 License

This framework is shared for educational and project demo purposes. Fork or reuse with proper credits.

---
