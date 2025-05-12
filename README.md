# Stripe Selenium Automation

Automated Stripe test payment using Java and Selenium WebDriver.

## 🔧 Technologies Used
Java

Selenium WebDriver

ChromeDriver

JUnit/TestNG (optional)

Maven (optional)

## 📄 Description
This project performs an end-to-end automated test of a Stripe test payment form using Selenium. It includes:

Filling out test email and card details

Clicking the Pay button

Handling the 3D Secure authentication iframe

Completing the transaction by clicking the "Complete" button in the popup

The script uses an official Stripe test card number: 4000002760003184 which simulates 3D Secure authentication flow.

## 📁 Project Structure
.
├── src
│ └── main
│ └── java
│ └── com
│ └── java_testing
│ └── Selinium_testing
│ └── App.java
│
├── drivers
│ └── chromedriver.exe
│
└── README.md

## 🚀 How to Run
Make sure Java and Chrome are installed.

Download ChromeDriver and place it in the path: /src/main/java/drivers/chromedriver.exe

Update the path if necessary in App.java.

## Run the application:

bash
Copy
Edit
javac App.java
java App
Or if using an IDE like IntelliJ or Eclipse, run App.java directly.

## 🧪 Test Data Used
Email: testuser@example.com

Card Number: 4000002760003184

Expiry Date: 12 / 34

CVC: 123

Billing Name: Test User

## ✅ Expected Behavior
Stripe test form is filled automatically.

Payment is triggered.

If 3D Secure appears, iframe is handled.

"Complete" button is clicked automatically.

Script completes with a message.

## 📌 Notes
This is a test flow using Stripe test credentials.

Intended for QA or automation demonstrations.

Do not use in production or with live credentials.

👤 Author
Sunny Choudhary

Final Year B.Tech Student, Heritage Institute of Technology
