# 🚀 Postman API Testing Practice Repository

> A collection of hands-on API testing projects built with **Postman**, covering **REST APIs**, **SOAP APIs**, **Mock APIs**, **Data-Driven Testing**, **End-to-End workflows**, and **Newman CLI automation**.

<p align="center">

![Postman](https://img.shields.io/badge/Postman-API%20Testing-FF6C37?logo=postman&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-0A66C2)
![SOAP API](https://img.shields.io/badge/SOAP-XML%20Testing-6C757D)
![JSON](https://img.shields.io/badge/JSON-Data-5E5CFF?logo=json&logoColor=white)
![JSON Server](https://img.shields.io/badge/JSON%20Server-Mock%20API-4CAF50)
![CSV](https://img.shields.io/badge/CSV-Data--Driven%20Testing-E67E22)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?logo=node.js&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-CLI%20Automation-00A98F)

</p>

---

# 🗂️ Overview

This repository contains a collection of **Postman API Testing projects** designed to strengthen API testing skills through practical, real-world examples.

The projects cover **REST APIs**, **SOAP APIs**, **JSON Server mock APIs**, **Data-Driven Testing using CSV files**, **End-to-End workflows**, and **Newman CLI automation**, making it an excellent learning resource for beginners and intermediate API testers.

---

# ✨ Features

- ✅ REST API Testing
- ✅ SOAP API Testing
- ✅ CRUD Operations
- ✅ JSON Server Mock APIs
- ✅ Data-Driven Testing using CSV
- ✅ End-to-End API Workflow Testing
- ✅ Postman Collection Runner
- ✅ Newman CLI Automation
- ✅ HTML Extra Reporting

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Postman | API Testing & Automation |
| REST APIs | CRUD Operations |
| SOAP APIs | XML Request & Response Validation |
| JSON Server | Mock API Backend |
| CSV | Data-Driven Testing |
| JSON | Request & Response Payloads |
| Node.js | Runtime Environment |
| Newman | CLI Collection Execution |
| HTML Extra Reporter | Interactive HTML Reports |

---

# 🏗️ Project Structure

```text
Postman_API_Testing/
│
├── collections/
│   ├── Project 1 - JSON Server (Dummy APIs).postman_collection.json
│   ├── Project 2 - SOAP.postman_collection.json
│   ├── Project 3 - Restful Booker.postman_collection.json
│   ├── Project 4 - E2E Scenario Testing.postman_collection.json
│   ├── Project 5 - Data Driven Testing.postman_collection.json
│   ├── Project 5 - Data Driven Testing.postman_test_runner.json
│   ├── Project 6 - Reqres.postman_collection.json
│   ├── Project 7 - JSONPlaceholder.postman_collection.json
│   └── Project 8 - FakeRestAPI_Authors.postman_collection.json
│
├── data/
│   └── Project 5 - CSV File for Data Driven Testing.csv
│
├── newman/
│   └── report.html
│
├── db.json
├── package.json
├── .gitignore
└── README.md
```

---

# 📚 Learning Projects

| No. | Project | Files | Description |
|----:|---------|-------|-------------|
| **01** | JSON Server (Dummy APIs) | `Project 1 - JSON Server (Dummy APIs).postman_collection.json` | CRUD testing using mock API endpoints |
| **02** | SOAP API Testing | `Project 2 - SOAP.postman_collection.json` | XML request and response validation |
| **03** | Restful Booker | `Project 3 - Restful Booker.postman_collection.json` | CRUD operations using Restful Booker APIs |
| **04** | End-to-End Scenario Testing | `Project 4 - E2E Scenario Testing.postman_collection.json` | Complete API workflow testing |
| **05** | Data-Driven Testing | `Project 5 - Data Driven Testing.postman_collection.json`<br>`Project 5 - Data Driven Testing.postman_test_runner.json`<br>`Project 5 - CSV File for Data Driven Testing.csv` | CSV-driven parameterized API testing |
| **06** | Reqres API | `Project 6 - Reqres.postman_collection.json` | CRUD operations and response validation |
| **07** | JSONPlaceholder | `Project 7 - JSONPlaceholder.postman_collection.json` | REST API testing practice |
| **08** | FakeRestAPI Authors | `Project 8 - FakeRestAPI_Authors.postman_collection.json` | CRUD operations on Authors resource |

---

# ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

### Install Dependencies

If you're using the JSON Server project:

```bash
npm install
```

### Start JSON Server

```bash
npx json-server db.json
```

### Import Collections

Import the required **Postman Collection (.json)** into Postman.

### Execute Collections

Collections can be executed using:

- **Postman Collection Runner**
- **Newman CLI**

---

# ▶️ Running Collections with Newman

### Install Newman

```bash
npm install -g newman
```

### Install HTML Extra Reporter

```bash
npm install -g newman-reporter-htmlextra
```

### Execute a Collection

```bash
newman run "<YOUR_COLLECTION_PATH>" ^
-r cli,htmlextra ^
--reporter-htmlextra-export "newman/report.html"
```

---

# 📊 Sample Newman HTML Report

Generate a report after executing your collection using Newman.

<p align="center">
<img width="1000" src="https://github.com/user-attachments/assets/f8c62e26-549b-4fdb-85a8-dfe156e0bfc1" alt="Newman HTML Report">
</p>

---

# 👨‍💻 Author

**Avinash Sinha**

If you found this repository helpful, consider giving it a ⭐ on GitHub.

---

# 📄 License

This repository is intended for **educational and practice purposes**.
