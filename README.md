Symbiosis Admission Registration System
A full-stack project featuring a responsive registration form and an automated testing suite developed with Selenium WebDriver (Java).

📝 Project Overview
This project was developed as a task to bridge the gap between frontend development and automated quality assurance. It involves creating a user-friendly admission form for Symbiosis and ensuring its reliability through automated test cases.

The Task:
Develop a registration form containing: Name, Email ID, Password, Confirm Password, Gender (Checkboxes), and Course (Dropdown).

🛠️ Features & Implementation
1. Frontend Development

Styling: Applied a blend of Internal and External CSS to create a modern, professional "Symbiosis" themed UI.

Validation: Implemented JavaScript logic to provide real-time feedback, ensuring passwords match and fields are correctly formatted.

2. Automation Suite

Functional Testing: Automated the process of entering data, selecting checkboxes, and choosing from the dropdown.

Wait Logic: Utilized WebDriverWait and ExpectedConditions to handle the asynchronous visibility of the "Success" modal.

📂 Project Structure
Plaintext
Symbiosis Admission Registration Form/
├── frontend/
│   ├── index.html       # Form Structure
│   ├── style.css        # UI Styling
│   └── script.js        # Validation Logic
├── backend (Selenium)/
│   ├── src/             # Java Automation Source Code
│   ├── .project         # Eclipse Project File
│   └── .classpath       # Build Path Configuration
└── README.md            # Project Documentation
🚀 Setup & Execution
Prerequisites:

Java JDK (Version 11+)

Eclipse IDE

Google Chrome browser

Configuration (External Libraries):
To keep this repository lightweight, Selenium JAR files are not included. Follow these steps:

Download the Selenium Java Bindings from Selenium.dev.

In Eclipse, right-click the project -> Build Path -> Configure Build Path.

Under Libraries, select Classpath and click Add External JARs to add all downloaded Selenium .jar files.

Download the ChromeDriver that matches your Chrome version.

Update the driver path in SymbiosisRegistration.java:
System.setProperty("webdriver.chrome.driver", "C:/path/to/your/chromedriver.exe");

💻 Technologies Used
Languages: HTML5, CSS3, JavaScript (ES6), Java

Automation: Selenium WebDriver

Tools: Git, GitHub, Eclipse IDE
