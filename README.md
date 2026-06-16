# API Testing Practice Projects  

![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman)
![JSON Server](https://img.shields.io/badge/JSON%20Server-Mock%20APIs-green)
![REST API](https://img.shields.io/badge/REST-API-blue)
![SOAP](https://img.shields.io/badge/SOAP-API-lightgrey)
![CSV](https://img.shields.io/badge/Data--Driven%20Testing-CSV%20Files-yellow)
![JSON](https://img.shields.io/badge/JSON-Data-lightblue?logo=json)
![Node.js](https://img.shields.io/badge/Node.js-JSON%20Server-brightgreen?logo=node.js)

---

## 🗂️ Overview

This repository contains multiple **API testing practice projects** created using **Postman**.

It covers a variety of testing approaches, including **REST APIs, SOAP APIs, JSON Server mock APIs, Data-Driven Testing, and End-to-End flows**.

All projects are provided as **Postman collections (.json)**, along with CSV test files where applicable.

---

## 🛠️ Tools & Technologies  

- **Postman** – API testing and automation
- **REST APIs** – CRUD testing
- **SOAP APIs** – XML-based request/response flows
- **JSON Server** – Mock/dummy API backend
- **CSV** – Data-driven testing with Postman Runner
- **Node.js** – Runtime for JSON Server
- **JSON** – Structured payload format
- **Newman** – CLI-based execution of Postman collections
- **HTML Extra Report** – Rich HTML Newman reporting

---

## 📘 Projects Covered  

| No.    | Project Name                     | Files Included                                                                                                          | Description                                       |
| ------ | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| **01** | JSON Server (Dummy APIs)         | `Project 1 - JSON Server (Dummy APIs).postman_collection.json`                                                          | Tested mock/dummy API endpoints using JSON Server |
| **02** | SOAP API Testing                 | `Project 2 - SOAP.postman_collection.json`                                                                              | SOAP XML request/response practice                |
| **03** | Restful Booker                   | `Project 3 - Restful Booker.postman_collection.json`                                                                    | CRUD operations using Restful-Booker API          |
| **04** | E2E Scenario Testing             | `Project 4 - E2E Scenario Testing.postman_collection.json`                                                              | Real-world end-to-end workflow testing            |
| **05** | Data Driven Testing (CSV)        | `Project 5 - CSV File for Data Driven Testing.csv`                                                                      | CSV-based data-driven testing                     |
| **05** | Data Driven Testing (Collection) | `Project 5 - Data Driven Testing.postman_collection.json`<br>`Project 5 - Data Driven Testing.postman_test_runner.json` | Collection + runner config                        |
| **06** | Reqres                           | `Project 6 - Reqres.postman_collection.json`                                                                            | CRUD API tests on Reqres                          |
| **07** | JSONPlaceholder                  | `Project 7 - JSONPlaceholder.postman_collection.json`                                                                   | REST testing with JSONPlaceholder APIs            |
| **08** | FakeRestAPI Authors              | `Project 8 - FakeRestAPI_Authors.postman_collection.json`                                                               | CRUD operations on FakeRestAPI Authors module     |

---

## 📊 Newman Reports (CLI + HTML Extra)

Newman reports are generated using:

```cmd
newman run "<YOUR_COLLECTION_URL_OR_FILE_PATH>" ^
-r cli,htmlextra ^
--reporter-htmlextra-export "newman\report.html"
```

#### ✅ Sample Newman HTML Report

<img width="1920" height="1656" alt="file" src="https://github.com/user-attachments/assets/93929e0a-517f-45d0-87d2-c4d2878ff35b" />

---

## 📌 Author

👤 Avinash Sinha

---

📝 This repository is created exclusively for **educational and practice use**.

---
