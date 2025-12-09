# ♻️ Java Design Patterns – Observer (Nivel 1)

## 📄 Description
**Exercise:**  
In this project, we implemented the **Observer design pattern** to simulate a **stock market notification system**.  

A `StockAgent` (**Observable**) monitors market changes (prices going up or down) and automatically notifies multiple `StockAgency` (**Observers**) that are subscribed to receive updates.

**Goal:** Ensure a loosely-coupled architecture where:  
- The Observable maintains references to all Observers.  
- Observers react autonomously to market changes.  
- New agencies can subscribe or unsubscribe dynamically.

## ⚙️ Functionalities
**Main features implemented:**  
- Register, remove, and notify observers.  
- Simulate stock market fluctuations (up/down).  
- Notify all subscribed Stock Agencies automatically.  
- Encapsulate the notification mechanism inside the Observable.  
- Demonstrate how multiple observers react differently to the same event.

**Class Responsibilities:**  
- `StockAgent.java` – The Observable that manages observer registration and sends notifications.  
- `Observer.java` – Interface defining `update(String marketStatus)`.  
- `StockAgency.java` – Concrete Observer implementing the `update()` method.  
- `Main.java` – Demonstrates registration, notification, and dynamic event propagation.

## 💻 Technologies Used
- Java JDK 24 (OpenJDK)  
- IntelliJ IDEA 2025.1  
- Git & GitHub  
- Concepts: Observer Pattern, Interfaces, Abstraction, Loose Coupling

## 📋 Requirements
- Java JDK 24+  
- IntelliJ IDEA 2025.1+  
- Basic understanding of:  
  - Object-Oriented Programming  
  - Behavioral Design Patterns (Observer)

## 🛠️ Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/yvangabrieli/S3.02.Patterns_2
   ´´´
