# **Testing Framework for Web Applications**

## **Overview**

This repository demonstrates the comprehensive testing process applied to web applications to ensure their functionality, scalability, and robustness. The testing framework leverages detailed test planning, execution of test cases, and efficient bug reporting using industry-standard tools like JIRA.

---

## **Testing Details**

### **Purpose of Testing**
The primary goal of this testing framework is to:
- Validate core application functionalities.
- Ensure the application is secure, reliable, and performs well under load.
- Identify and resolve bugs in a structured manner.

### **Testing Process**
1. **Test Planning**: Define the testing scope, objectives, and levels.
2. **Test Execution**: Use test cases to systematically validate all application modules.
3. **Bug Reporting**: Track and resolve identified issues using JIRA for collaboration.
4. **Regression Testing**: Re-run critical test cases after bug fixes to ensure no side effects.

---

## **About the Project Under Test**

### **Hackathon Experience and Research Sharing Platform**
The testing framework is applied to a **MERN stack** platform, which I developed to facilitate the sharing of **hackathon experiences** and **research papers**. Below are the key features of the project:

#### **Project Features**
- **CRUD Operations**: Enables creating, reading, updating, and deleting user-generated content.
- **Media Management**: Implements efficient file storage and delivery via **Cloudinary**.
- **Secure Authentication**: Integrates **JWT** and **Google Authentication** for user security.
- **Optimized Architecture**: Applies the **Single Responsibility Principle** for maintainable code.
- **Search Functionality**: Enables users to find relevant content with minimal load time.

---

## **Test Plan**

### **Objectives**
- Validate login, registration, and user profile functionalities.
- Test dashboard features for CRUD operations.
- Ensure efficient search results under various scenarios.

### **Scope**
- **Modules Tested**:
  - User Login and Registration
  - Dashboard CRUD Operations
  - Search Functionalit

---

## **Test Cases**

### **Sample Test Cases**

| Scenario TID | Test Scenario         | Test Case ID | Test Data                                                                                         | Test Case Title                                                                                                                                                 | Pre Condition                                                                                                                           | Steps to Execute                                                                                                                                                                                                                                                                                               | Expected Result                                                                             | Actual Result                                                                               | Status | Executed QA Name | Misc (Comments) | Priority | Is Automated | 
| ------------ | --------------------- | ------------ | ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------ | ---------------- | --------------- | -------- | ------------ | 
| 1            | HRH Login Page        | 1            | Email - abc112@gmail.com, Password - Abcdef@12345                                                 | [Verify that the Login should work with the Valid User and password.](https://hackathon-research-hub.vercel.app/)                                               | [hackathon-research-hub.vercel.app/auth/login Login Page is loaded.](https://hackathon-research-hub.vercel.app/auth/login)              | [1\. Navigate to the Application hackathon-research-hub.vercel.app/ 2. Enter Email "abc112@gmail.com" and Password "Abcdef@12345".<br>3\. Click on the Login button](https://hackathon-research-hub.vercel.app/auth/login)                                                                                     | Login should work with valid CREDENTIALS                                                    | Login is working with Valid CREDENTIALS                                                     | Pass   | Yashraj          |                 | P0       | No           |  
| 1            | HRH Login Page        | 2            | Enter Invalid email : xyz213@gmail.com ,<br>Valid Password - Abcdef@12345                         | [Verify that the Login shouldn't work with the invalid User and password.](https://hackathon-research-hub.vercel.app/)                                          | [hackathon-research-hub.vercel.app/auth/login Login Page is loaded.](https://hackathon-research-hub.vercel.app/auth/login)              | [1\. Navigate to the Application hackathon-research-hub.vercel.app/ 2. Enter Email "xyz213@gmail.com" and Password "Abcdef@12345".<br>3\. Click on the Login button](https://hackathon-research-hub.vercel.app/auth/login)                                                                                     | Login should NOT work with invalid CREDENTIALS                                              | Login is not working with Invalid CREDENTIALS                                               | Pass   | Yashraj          |                 | P0       | No           |
| 1            | HRH Login Page        | 3            | N/A                                                                                               | Verify that the login page has a user-friendly and intuitive design, with clear labels for the Email and password fields and a visible login button.            | [hackathon-research-hub.vercel.app/ Page is loaded.](https://hackathon-research-hub.vercel.app/)                                        | [1\. Navigate to the Application hackathon-research-hub.vercel.app/ 2. Observe the design elements of the login page including labels and button visibility.](https://hackathon-research-hub.vercel.app/auth/login)                                                                                            | Login page should be user-friendly with clear labels and visible buttons.                   | Login page is user-friendly with clear labels and visible buttons.                          | Pass   | Yashraj          |                 | P1       | No           | 

---

## **Conclusion**

This testing framework ensures that the platform is robust, secure, and optimized for the best user experience. Through structured testing and efficient bug tracking, the project under test has been refined to meet high standards of quality and reliability.

---
