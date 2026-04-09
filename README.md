# ⚖️ Legal Sahayak

**Legal Sahayak** is a comprehensive legal awareness and assistance application designed to empower citizens with knowledge of their legal rights. Built with a **Java Swing GUI** and a **SQLite backend**, it provides an intuitive interface for navigating complex legal landscapes, maintaining personal evidence logs, and generating formal legal documents like RTI requests.

---

## 🚀 Key Features

- **User Authentication**  
  Secure login and registration system using **jBCrypt** for robust password hashing.

- **Rights Navigator**  
  Browse various legal categories to view detailed summaries, key rights, and find contact information for specialized lawyers.

- **Evidence Log**  
  Private CRUD (Create, Read, Update, Delete) system for users to log incidents or harassment with automated timestamps and category tagging.

- **RTI Generator**  
  Automates the generation of formal Right to Information (RTI) requests and allows users to track their filing status directly within the app.

- **Legal Quiz**  
  Interactive module to test legal knowledge with instant feedback, scoring, and detailed explanations.

- **Jargon Buster**  
  Dedicated search tool to instantly find simplified definitions for complex legal terms.

- **Admin Tools**  
  Role-based access for administrators to manage lawyer profiles, update legal information content, and moderate the jargon database.

---

## 🛠️ Technology Stack

- **Language:** Java  
- **UI Framework:** Java Swing  
- **Database:** SQLite  
- **Security:** jBCrypt  

---

## 📂 Project Structure

The project follows a clean service-oriented architecture:

- `com.legalsahayak.app.ui` → Main entry point and `MainFrame` container managing the application's `CardLayout` for seamless panel switching.  
- `com.legalsahayak.app.db` → Handles database connectivity and SQL execution via `SqliteDatabaseService`.  
- `com.legalsahayak.app.service` → Core business logic, including `AuthService` for managing user registration and sessions.  
- `com.legalsahayak.app.model` → Defines data structures such as `UserSession`, `LogEntry`, `QuizCard`, and `LawyerProfile`.  

---

## 📝 Setup and Installation

### Prerequisites
- Java Development Kit (JDK) 8 or higher  
- SQLite JDBC Driver  

### Database Configuration
- The application looks for `legalsahayak.db` in the root directory.  
- Uses `PRAGMA foreign_keys = ON;` to ensure data integrity.  

### Running the Application
Launch the application by running the `com.legalsahayak.app.ui.Main` class.  

---

## 🆘 Emergency Support

The **Evidence Log** includes a **"Need Help Now?"** feature providing emergency contacts for:

- **Emotional Support:**  
  Resources like *Kiran Mental Health Rehab* and *Vandrevala Foundation*.  

- **Legal & Domestic Support:**  
  Contacts for the *National Commission for Women (NCW)* and *NALSA (Free Legal Aid)*.  

---

## 📜 License
This project is intended for educational and awareness purposes. Please ensure compliance with local laws when using or extending this application.
