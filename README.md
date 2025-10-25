# Browser History Manager — Stack & Deque Simulation (Java GUI)

A Java Swing application that simulates browser history using **Stack (Back)** and **Deque (Forward)** data structures.  
Featuring a simple dark-theme GUI to help understand real browser navigation behavior.

---

## ✅ Features
- Back navigation using **Stack — LIFO**
- Forward navigation using **Deque — FIFO**
- Clean & interactive GUI
- Real-time history updates
- Compact and beginner-friendly code

---

## 🛠 Technology Used
- **Java (JDK 21 Recommended)**
- **Swing** for GUI
- **Stack & ArrayDeque** for history logic

---

## 🚀 How to Run

### Using Command Line:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
javac BrowserHistoryManager_Creative.java
java BrowserHistoryManager_Creative
✅ The application window will launch

📘 Learning Concepts
Concept	Purpose
Stack	Implement Back button behavior
Deque	Implement Forward button behavior
Swing	GUI creation and event handling
DSA + UI	Real-world practical application

📂 Project Structure
Copy code
BrowserHistoryManager_Creative.java
README.md
🔄 Navigation Rules
Operation	What Happens
Visit new page	Current → Back stack, Forward history cleared
Back	Move current → Forward deque, Pop from Back to new current
Forward	Move current → Back stack, Pop from Forward to new current

🤝 Contributing
Feel free to fork and improve this project!
Pull Requests are welcome ✅

📜 License
Licensed under MIT License
You are free to modify and use this project for learning purposes!
