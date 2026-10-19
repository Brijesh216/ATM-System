# 🏦 ATM-System

A **Java Swing-based ATM System** with a modern **FlatLaf GUI** and **MySQL database integration**.  
It simulates core ATM functionalities such as deposit, withdrawal, balance inquiry, and transaction history with multi-user support.  

---

## 🚀 Features  
- ✅ **Secure Login** with Username & PIN  
- ✅ **Deposit, Withdraw, Balance Inquiry**  
- ✅ 📜 **Mini-Statement (Transaction History)**  
- ✅ ⏳ **Daily Withdrawal Limit**  
- ✅ 👥 **Multi-User Support** with MySQL backend  
- ✅ 🎨 **Modern GUI with FlatLaf Look & Feel**  

---

## 🖼️ Demo  
🎥 *Watch the video demo here*.  
https://lnkd.in/p/d7U23Z7T

---

## 🛠️ Tech Stack  
- ☕ **Java (Swing GUI + FlatLaf)**  
- 🗄️ **MySQL + JDBC** (Database Integration)  
- 📦 **Maven** (Dependency & Build Management)  
- 🖥️ **IntelliJ IDEA / Eclipse** (Development IDE)  

---

## ⚙️ Installation & Usage  

```bash
# 📥 Clone the repository
git clone https://github.com/Brijesh216/ATM-System-CodSoft.git
#Add MySQL Connector/J dependency (already included in pom.xml)
# Open the project in your IDE (IntelliJ/Eclipse)
# ▶️ Run the main class:
ATMSystem.java
```
## 🗄️ Database Setup (MySQL)

```sql
CREATE DATABASE atmdb;

CREATE TABLE accounts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) UNIQUE,
    pin VARCHAR(10),
    balance DOUBLE
);

-- Insert some sample data:
INSERT INTO accounts (username, pin, balance) 
VALUES ('brijesh', '1234', 5000.00);
```
## 👨‍💻 Author 

**Brijesh Prasad** 

🌐 Connect with me: 
- 🔗 [LinkedIn](https://www.linkedin.com/in/brijesh216) 
- 💻 [GitHub](https://github.com/brijesh216)
