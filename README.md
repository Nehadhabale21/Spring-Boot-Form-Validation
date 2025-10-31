# 🧾 Spring Boot Form Validation 

This is a simple **Spring Boot + Thymeleaf** project demonstrating how to perform **server-side form validation** using **Jakarta Validation** annotations.

---

## 🚀 Features

- ✅ Spring Boot (v3.5.7)
- 🧩 Thymeleaf templating engine
- 🧠 Jakarta Bean Validation 
- 🧰 Validation with `@Valid`, `BindingResult`, and error messages
- 🎨 Bootstrap 5 styling
- 🔄 Live reload with Spring Boot DevTools

---

## 🏗️ Project Structure

BootSpringValidation/
│
├── src/main/java/com/validate/
│ ├── BootSpringValidationApplication.java # Main application entry point
│ ├── controller/
│ │ └── MyController.java # Handles form routes and validation
│ └── entities/
│ └── LoginData.java # Model class with validation annotations
│
├── src/main/resources/
│ ├── templates/
│ │ ├── form.html # Form page with validation feedback
│ │ └── success.html # Success page
│ └── application.properties # Spring Boot configuration (optional)
│
├── pom.xml # Maven dependencies and configuration
└── README.md # Project documentation


---

## 📚 Technologies Used

| Component | Description |
|------------|-------------|
| **Spring Boot** | Framework for rapid Java development |
| **Thymeleaf** | Server-side template engine for rendering HTML |
| **Jakarta Validation (Bean Validation)** | Validation framework used for input validation |
| **Bootstrap 5** | Frontend UI framework for styling |
| **Maven** | Build and dependency management tool |

---
## 🖼️ Screenshots

### 🧾 Form Page
<img width="1457" height="615" alt="image" src="https://github.com/user-attachments/assets/f0e64792-f4e4-4a0b-9d81-d2de25e5761a" />

### 🧾 ⚠️ Error Handling Page (invalid input)
<img width="1366" height="760" alt="image" src="https://github.com/user-attachments/assets/65d3855d-c362-4f0d-a69e-21c01fb76183" />

### ✅ Success Page
<img width="837" height="422" alt="image" src="https://github.com/user-attachments/assets/7d5ebe32-df03-41f0-9594-5d85b8c4af54" />
