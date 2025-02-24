# Contributor Guidelines

Thank you for your interest in contributing! This repository is dedicated to maintaining well-structured and high-quality test cases. Please follow these guidelines to ensure consistency and clarity.

---

## 📂 Folder Structure

Test cases are organized as follows:

1. **`content/`** – The main directory where all test cases are stored, categorized by project type (e.g., `Web Apps`).
2. **Project Type Folder (e.g., `Web Apps/`)** – Contains subfolders for different types of testing.
3. **Test Type Folder (e.g., `Functional Testing/`, `Security Testing/`, `Usability Testing/`)** – Groups test cases by their testing category.
4. **Test Suite Folder (e.g., `Navigation/`, `Form Validation/`, `Search Functionality/`)** – Contains related test cases.
5. **Test Case Files** – Each test case is stored as a separate `.md` file inside the relevant suite folder.

### **Example Folder Structure**
```plaintext
content/
│── Web Apps/
│   │── Functional Testing/
│   │   │── Navigation/
│   │   │   │── Verify Homepage Loads.md
│   │   │   │── Verify Navigation Links.md
│   │   │── Form Validation/
│   │   │   │── Verify Email Field Validation.md
│   │── Security Testing/
│   │   │── Authentication/
│   │   │   │── Verify Login Security.md
│── TEMPLATE.md
│── CONTRIBUTING.md

```

---

## 🚀 How to Contribute

1. **Fork the Repository** – Click the "Fork" button to create a copy in your GitHub account.
2. **Create a Branch** – Use a meaningful branch name (e.g., `add-navigation-test`).
3. **Navigate to the Correct Folder** – Locate the appropriate directory based on the type of test case.
4. **Create a New Test Case File**  
   - Add a new `.md` file inside the correct test suite folder (e.g., `Verify Homepage Loads.md`).
   - Copy the contents of [`TEMPLATE.md`](TEMPLATE.md) into the new file.
   - Edit and complete the test case details.
5. **Commit Your Changes** – Use clear and descriptive commit messages.
6. **Submit a Pull Request**  
   - Ensure all sections of the pull request template are completed.
   - Submit your PR against the `stage` branch.
7. **Review Process**  
   - A maintainer will review your submission and may request changes.
   - Once approved, your contribution will be merged.

---

## ✅ Contribution Best Practices

- Follow the **folder structure** and **naming conventions** for consistency.
- Use **clear and concise language** in test cases.
- Ensure **proper formatting** for readability.
- Test cases should be **well-structured, precise, and reproducible**.

By following these guidelines, you help maintain a high-quality and well-organized repository. We appreciate your contributions! 🎉

Happy Testing! 🧪🚀