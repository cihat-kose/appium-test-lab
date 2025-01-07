
# Appium Test Lab

![Appium](https://img.shields.io/badge/Appium-6DB33F?style=for-the-badge&logo=appium&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF7300?style=for-the-badge&logo=testng&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

### 🚀 Overview
**Appium Test Lab** simplifies mobile application testing automation.  
This project allows you to create test scenarios using **TestNG** and **Appium** for **Android** platforms.  
It supports running tests on **emulators** and **real devices**.

---

### 🔧 Prerequisites
Ensure you have the following software installed on your system:

- Java JDK 11 or higher  
- Apache Maven  
- Node.js and npm  
- Appium Server  
- Appium Inspector  
- Android SDK  
- Android Emulator or Physical Android Device  

---

### ⚙️ Setup
#### 1. Clone the Project
```bash
git clone https://github.com/cihat-kose/appium-test-lab.git
cd appium-test-lab
```

#### 2. Install Maven Dependencies
```bash
mvn clean install
```

---

### ▶️ Running Tests
Follow these steps to run tests:

1. Start an **Android Emulator** or connect a **physical device**.  
2. Run tests through Maven:  
   ```bash
   mvn test
   ```
3. To run a specific test class:  
   ```bash
   mvn -Dtest=day02.C03_CalculatorTest test
   ```

---

### 📁 Project Structure
```plaintext
appium-test-lab
│
├── app                     # APK files for testing
│   ├── Android.apk
│   ├── ApiDemos.apk
│   ├── ApKINFO.apk
│   └── Calculator.apk
│
├── src
│   └── test
│       └── java
│           ├── day01
│           │   └── Appium.pdf
│           ├── day02
│           │   ├── C01_SetUpCapabilities
│           │   ├── C02_DifferentDrivers
│           │   └── C03_CalculatorTest
│           ├── day03
│           │   └── C04_CreateDriverClass
│           ├── day04
│           │   └── C05_AndroidTestApk
│           ├── day05
│           │   └── C06_ApiDemosTest
│           ├── day06
│           │   ├── C07_BrowserTest
│           │   └── C08_HerokuapTest
│           ├── page
│           └── utils
│
├── configuration.properties
├── LICENSE
├── pom.xml
└── README.md
```

---

### 🤝 Contributing
To contribute to this project, follow these steps:

1. **Fork** the repository 🍴  
2. Create a new **branch**:  
   ```bash
   git checkout -b feature/new-feature
   ```  
3. Make your changes and commit:  
   ```bash
   git commit -m "Added a new feature"
   ```  
4. **Push** your branch:  
   ```bash
   git push origin feature/new-feature
   ```  
5. Open a **Pull Request (PR)**!  

All contributions are welcome.  
Please ensure the project structure and coding standards are followed.  

---

### 📜 License
This project is licensed under the **MIT License**.  
For more details, refer to the [LICENSE](LICENSE) file.
