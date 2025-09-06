# CS Portfolio Automation

This project was developed as part of my **Computer Science coursework at SNHU**.  
It demonstrates **object-oriented programming in Java**, **JUnit testing with 80%+ coverage**, and **secure coding practices** through a simple Contact/Task/Appointment service system.

---

## 📌 Features
- Contact Service → Manage contacts with validation on ID, name, phone, and address.  
- Task Service → Manage tasks with constraints on ID, name, and description length.  
- Appointment Service → Schedule appointments, ensuring dates aren’t set in the past.  
- JUnit Tests → 80%+ coverage with assertions for constraints, edge cases, and error handling.  
- Secure Development Practices → Input validation, exception handling, and boundary testing.

---

## 🛠 Tech Stack
- Language: Java  
- Testing: JUnit  
- Tools: GitHub for version control, IntelliJ/Eclipse (IDE)  

---

## 📂 Project Structure
**Source files (planned structure):**  
- Contact.java  
- ContactService.java  
- ContactServiceTest.java  
- ContactTest.java  

**Docs:**  
- pj2_reflect.docx → Reflection write-up  
- README.md → This file  

---

## 🧪 Example Unit Test
Contact ID must be less than or equal to 10 characters:

```java
assertThrows(IllegalArgumentException.class, () -> {
    new Contact("12345678901", "John", "Doe", "1234567890", "123 Elm St");
});

🚀 How to Use

Clone the repo:
git clone https://github.com/collynk/CS_Portfolio_Automation.git

Open in IntelliJ/Eclipse.

Run the JUnit tests to validate services.

🎓 Academic Context

This project is part of my SNHU Computer Science portfolio.
It showcases:

Writing modular Java classes.

Aligning code with software requirements.

Applying unit testing and boundary testing.

Thinking about security and code quality early in the lifecycle.

📈 Future Improvements

Add integration and system tests.

Expand documentation with UML class diagrams.

Automate JUnit test runs with GitHub Actions (CI/CD).
