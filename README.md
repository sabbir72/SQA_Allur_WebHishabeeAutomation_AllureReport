Allure report Screenshort

http://192.168.1.106:57360/index.html

![Screenshot_18](https://github.com/sabbir72/WebHishabeeAutomation_AllureReport/assets/73008358/279f3000-95f0-449a-9033-c60f3e0846dd)

# WebHishabeeAutomation_AllureReport![Uploading Screenshot_18.jpg…]()


# **Project Analysis: SQA_Allur_WebHishabeeAutomation_AllureReport**

## **📌 Overview**
This GitHub repository contains an **automated testing framework** for **WebHishabee** (a web application) with **Allure Report** integration. It appears to be a **Selenium WebDriver** project using **TestNG** and **Allure** for reporting.

---

## **🔍 Key Components**
### **1. Test Automation Stack**
- **Language**: Java  
- **Testing Framework**: TestNG  
- **Reporting**: Allure Framework  
- **Browser Automation**: Selenium WebDriver  
- **Build Tool**: Likely Maven (common for Java projects with Allure)  

### **2. Key Features**
✅ **Allure Report Integration** – Generates detailed HTML reports with graphs, steps, and screenshots.  
✅ **WebHishabee UI Testing** – Automated test cases for the web application.  
✅ **Structured Framework** – Follows **Page Object Model (POM)** for maintainability.  

---

## **🚀 How to Run This Project**
### **Prerequisites**
1. **Java JDK 8+**  
2. **Maven** (for dependency management)  
3. **Allure Commandline** (for report generation)  

### **Steps**
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/sabbir72/SQA_Allur_WebHishabeeAutomation_AllureReport.git
   cd SQA_Allur_WebHishabeeAutomation_AllureReport
   ```

2. **Install Dependencies**  
   ```bash
   mvn clean install
   ```

3. **Run Tests**  
   ```bash
   mvn test
   ```

4. **Generate Allure Report**  
   ```bash
   allure serve allure-results
   ```
   *(This opens an interactive HTML report in your browser.)*

---

## **📊 Expected Allure Report Output**
The report will include:  
📈 **Graphs** (Duration, Status Trends)  
📋 **Test Suites** (Passed/Failed/Broken)  
🔍 **Detailed Steps** (Logs, Screenshots if configured)  

*(Example: Similar to BlazeMeter but for functional testing.)*  

---

## **🔧 Potential Improvements**
1. **Add Screenshot on Failure** – Helps debug UI issues.  
2. **Integrate CI/CD** (GitHub Actions/Jenkins) – For automated test runs.  
3. **Add API Testing** – Using RestAssured for full coverage.  

---

## **💡 Why This Project Matters**
- **End-to-End Testing** – Ensures **WebHishabee** works as expected.  
- **Professional Reports** – Allure provides **stakeholder-friendly** insights.  
- **Reusable Framework** – Easy to add more test cases.  

---

### **🚀 Next Steps?**  
Want a **step-by-step guide** to extend this framework? **Star the repo & let me know!** ⭐  

