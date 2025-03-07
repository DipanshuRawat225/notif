# POC on Unit Testing for Frontend



| **Author** | **Created on** | **Version** | **Last updated by**|**Internal Reviewer** |**Reviewer L0** |**Reviewer L1** |**Reviewer L2** |
|------------|---------------------------|-------------|---------------------|-------------|-------------|-------------|-------------|
| Dipanshu Rawat|   07-03-2025             | v1          | Dipanshu Rawat        |  Siddharth Pawar |  |   |      |



## Table of Content: 
- [Introduction](#Introduction)
- [Step-by-Step setup Guide](#Step-by-step-Setup-Guide)
- [Conclusion](#Conclusion)
- [Contact Information](#Contact-Information)
- [References](#References)

## Introduction
In this POC, We will use most popular Unit Test Tool - Jest for our Frontend application. We will see step by step setup guide, will do Unit Test. 

---

# Step-by-Step Setup Guide

### **Step 1**: Go to your Frontend directory

```
cd Frontend/
```
---

### **Step 2**: Install NPM

- Install Frontend dependencies
```
sudo apt install npm
````
---

### **Step 3**: Check Jest Version

- Go inside your package.json and look for jest: 
![Screenshot (373)](https://github.com/user-attachments/assets/d646eb0f-2924-4b27-bed8-9a1f8292a3b4)


- Install jest
```
npm install --save-dev jest@23.6.0 babel-jest@23.6.0
```
![Screenshot (374)](https://github.com/user-attachments/assets/23c8eafd-fe70-409a-8d2c-af411f4b7db1)

---

### **Step 4**: Run npm test 

run npm test for Unit testing.
```
npm test
```
![Screenshot 2025-03-08 003937](https://github.com/user-attachments/assets/1f309349-0fbd-44dc-aff4-1313adc4de09)


---

## Conclusion

Unit testing is a crucial part of modern frontend development, ensuring application stability and reducing potential bugs. By integrating Jest into your workflow, you can efficiently test components and functions, leading to a more robust and maintainable application. This POC demonstrates the fundamental steps to set up Jest, write test cases, and execute them successfully.
---

## Contacts

| Name| Email Address      |
|-----|--------------------------|
| Dipanshu Rawat | dipanshu.rawat@mygurukulam.co |  
 
---

## Reference Links

| Link | Description |
|------|------------|
| [**Jest Official Documentation**](https://jestjs.io/docs/getting-started) | Official Jest documentation covering installation, setup, and advanced usage. |
| [**Jest Testing Guide**](https://jestjs.io/docs/tutorials) | A beginner-friendly guide to writing unit tests using Jest. |
