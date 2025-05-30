# ATX Automation Agent (A3)

**A3** is a multi-agent AI system that **automates backend API testing** using advanced AI/GenAI models. It generates **executable integration test cases** by analyzing API specifications and test scenarios, ensuring complete API coverage with **no code/data/IP leak**.

Hosted securely on customer on-premise/cloud environments, A3 accelerates QA with intelligent test case generation and reporting.

![A3 UI Preview](images/a3_1.png)

---

## 🚀 Features

1. ✅ **Executable test code** generated for backend APIs in designated output folders  
2. 📄 **Reads directly from**:
   - Postman Collections
   - Swagger/OpenAPI specs
   - Other well-structured API documentation  
3. 🤖 **AI-driven test case generation** from plain English integration/system test scenarios
4. 🧠 **Automatically discovers API dependencies** to create effective integration test plans
5. 📑 Enhanced test coverage with:
   - Product requirement documents
   - Custom test case scenarios
6. 📊 **Allure Reports** for visualizing test execution
7. 📁 **A3 Management Console** to manage and track multiple projects with ease
8. 🧪 Covers diverse test categories:
   - Successful flow
   - Failure tests (invalid tokens, bad payloads)
   - Synthetic data variations for edge cases
   - Custom data from client sources

---

## 📦 Requirements

- Visual Studio Code (v1.70+)
- Node.js (for test execution)
- Allure CLI (for reporting): [Install Allure](https://docs.qameta.io/allure/#_installing_a_commandline)



---
## ▶️ How to Start A3

1. Open the Command Palette with `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS)
2. Type and select: **Start A3 API**

```plaintext
> Start A3 API

---

## 📋 Release Notes

### 1.0.0

- Initial release of ATX Automation Agent (A3)
- Supports Swagger/Postman inputs, AI-based test generation, Allure reports

---

## ✍️ Contributing

To contribute to this extension, clone the repo, make changes, and test with:

```bash
vsce package
