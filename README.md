# 🚀 Postman API Testing Practice Repository

> A hands-on collection of **Postman API Testing** projects covering **REST APIs**, **SOAP APIs**, **Mock APIs**, **Data-Driven Testing**, **End-to-End Workflows**, and **Newman CLI Automation**.

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

This repository contains a collection of **Postman API Testing** projects created to strengthen API testing skills through practical, real-world examples.

The projects cover **REST APIs**, **SOAP APIs**, **Mock APIs using JSON Server**, **Data-Driven Testing with CSV files**, **End-to-End API workflows**, and **Newman CLI automation**, making this repository a comprehensive learning resource for mastering API testing with Postman.

---

# ✨ Repository Highlights

- ✅ REST API Testing
- ✅ SOAP API Testing
- ✅ CRUD Operations
- ✅ Mock APIs using JSON Server
- ✅ Data-Driven Testing using CSV
- ✅ End-to-End API Workflow Testing
- ✅ Postman Collection Runner
- ✅ Newman CLI Automation
- ✅ HTML Extra Reporting

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **Postman** | API Testing & Automation |
| **REST APIs** | CRUD Operations |
| **SOAP APIs** | XML Request & Response Validation |
| **JSON Server** | Mock API Backend |
| **CSV** | Data-Driven Testing |
| **JSON** | Request & Response Payloads |
| **Node.js** | Runtime Environment |
| **Newman** | CLI Collection Execution |
| **HTML Extra Reporter** | Interactive HTML Reports |

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

# 📚 Projects Included

| No. | Project | Description |
|----:|---------|-------------|
| **01** | JSON Server (Dummy APIs) | CRUD testing using mock API endpoints |
| **02** | SOAP API Testing | XML request and response validation |
| **03** | Restful Booker | CRUD operations using Restful Booker APIs |
| **04** | End-to-End Scenario Testing | Complete API workflow testing |
| **05** | Data-Driven Testing | CSV-driven parameterized API testing |
| **06** | Reqres API | CRUD operations and response validation |
| **07** | JSONPlaceholder | REST API testing practice |
| **08** | FakeRestAPI Authors | CRUD operations on Authors resource |

---

# ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

### Install Dependencies

If you are using the **JSON Server** project:

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

Run the collections using either:

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

# 📊 Newman HTML Report

Generate an interactive HTML report after executing your collection with Newman.

<p align="center">
<img width="1000" src="https://github.com/user-attachments/assets/f8c62e26-549b-4fdb-85a8-dfe156e0bfc1" alt="Newman HTML Report">
</p>

The generated report provides detailed execution statistics, request and response information, assertion results, response times, and overall collection execution summaries.

---

# ⭐ Repository Highlights

- 📮 Covers REST and SOAP API testing with Postman
- 📂 Includes eight practical API testing projects
- 🔄 Demonstrates complete CRUD operations
- 🧪 Supports Data-Driven Testing using CSV files
- 🖥️ Includes Mock API development using JSON Server
- ⚡ Automates collection execution with Newman CLI
- 📊 Generates interactive HTML execution reports
- 🏗️ Well-organized project structure for learning and practice

---

# 👨‍💻 Author

**Avinash Sinha**

If you found this repository useful, consider giving it a ⭐.

---

# 📄 License

This repository is intended for **educational**, **learning**, and **practice purposes**.
