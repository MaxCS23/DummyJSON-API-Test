# 🧪 API Testing Automation with Postman & GitHub Actions

This repository contains an automated API testing framework using Postman and GitHub Actions. It demonstrates key skills in continuous integration, test structuring, and secure API workflows.

## 🚀 Project Goals

- Automate endpoint validation using Postman tests.
- Execute test suite on code changes and via manual dispatch.
- Showcase secure authentication flows and session management.
- Illustrate clean testing strategies with reusable components.

## 🧰 Technologies Used

- 🧪 Postman (collections, environment variables, test scripts)
- ⚙️ GitHub Actions (CI/CD workflows)
- 🌐 DummyJSON API (sample API for testing)
- 🔐 JWT / API Key / Cookies (authentication and security)
- 📄 Markdown (documentation)

## ⚙️ Test Execution

### Manual Trigger
Via GitHub → Actions → `Run workflow`.

### Automatic Trigger
Tests run on every push to the repository.

## 🔐 Authentication and Security

- JWT used to secure sensitive endpoints.
- Login workflows tested, with session persistence via cookies.
- Dynamic token and header management through environment variables.
  
## 🖼️ Test Highlights
- Status code validations: 200, 404, 401, etc.
- Assertions on response body and headers.
- Session continuity across authenticated requests.

## 📦 How to Import the Collection

To explore or run the test suite locally using Postman:

1. Open [Postman Web](https://web.postman.com) or the Postman desktop app.
2. Click **Import** at the top-left corner.
3. Select the tab **"Link"** or **"File"** depending on what you're using:
   - If using a public collection link: paste the URL provided.
   - If using a local file: upload `collection.json` and `environment.json`.
4. After importing:
   - Choose the appropriate environment from the dropdown.
   - Click **Run** or use the **Collection Runner** for batch testing.
     
## 📜 License
MIT License — Free to use for educational and professional purposes.

## 👤 Author
Max Cortes Serrano
QA Engineer
[LinkedIn Profile](https://www.linkedin.com/in/max-cortés-6a132b21b)
Email: maxcortes23@gmail.com



