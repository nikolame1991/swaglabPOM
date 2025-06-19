🔐 SauceDemo Automation Project (Selenium + Java + TestNG + POM)

This project demonstrates test automation of saucedemo.com using:

    Selenium WebDriver

    Java

    TestNG

    Page Object Model (POM)

    Explicit Waits

🧱 Project Structure

(Opiši ovde strukturu foldera i fajlova, npr.):

swaglabPOM/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── pageClasses/       # Page Object Model classes
│   ├── test/
│       └── java/
│           └── testClasses/       # TestNG test classes
├── testng.xml                    # TestNG suite file
├── pom.xml / build.gradle (if any)
└── README.md

🧪 Test Scenarios

The LoginPageTest.java class covers the following scenarios:

    ❌ Login without credentials → expected message: Epic sadface: Username is required

    ❌ Only password entered → expected message: Epic sadface: Username is required

    ❌ Only username entered → expected message: Epic sadface: Password is required

    ❌ Invalid credentials → expected message: Epic sadface: Username and password do not match any user in this service

    ✅ Valid credentials → expected redirect to URL ending with /inventory.html

🛠️ Technologies Used

    Java 17+

    Selenium WebDriver

    TestNG

    Page Object Model (POM)

    WebDriverWait (Explicit Waits)

    ChromeDriver

🚀 How to Run the Project

    Clone the repository:

    git clone https://github.com/nikolame1991/swaglabPOM.git

    Open the project in your favorite IDE (IntelliJ IDEA recommended)

    Make sure you have ChromeDriver set up and in your PATH or configure its location in the code

    Run TestNG test classes like LoginPageTest or use testng.xml suite file

    Observe results in TestNG reports and console logs

👨‍💻 Author

Nikola Medan
QA Automation Engineer
📧 nikolamedan1991@gmail.com
🔗 LinkedIn
🔗 GitHub
