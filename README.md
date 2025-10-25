# Browser History Manager — Stack & Deque Simulation (Java GUI)

This project demonstrates how real web browsers manage history using **Stack (Back)** and **Deque (Forward)** data structures.  
It features a simple GUI where users can visit pages, go back, and move forward just like in Google Chrome or Firefox.

---

## 🎯 Project Objective
To visually understand and implement browser navigation history using **Data Structures** in Java.

---

## 🧠 Why Stack & Deque?
| Feature in Browsers | Data Structure Used | Reason |
|-------------------|------------------|-------|
| Go **Back** to previous pages | **Stack (LIFO)** | Last visited page should come back first |
| Go **Forward** to recently reversed pages | **Deque (FIFO / Double-Ended Queue)** | Can insert/remove from both ends efficiently |

📌 **Deque is used because:**
- When a new page is visited → Forward history must clear
- It gives flexible insertions/removals

---

## ⚙️ How It Works — Internal Logic
| Action | Back Stack | Forward Deque |
|--------|------------|---------------|
| ✅ Visit New Page | Push current page | Clear forward deque |
| 🔙 Back Button | Pop from Back → Current | Push old current to Forward |
| 🔜 Forward Button | Pop from Forward → Current | Push old current to Back |

> This behavior **perfectly matches** actual browser navigation!

---

## ✅ Features
- User can **visit**, **back**, and **forward** pages
- History displayed clearly in GUI
- Dynamic updates after every action
- Modern dark-theme interface
- Compact implementation with comments

---

## 📘 Real-World Use Cases
| Application | Uses Stack / Deque? | Description |
|------------|-------------------|-------------|
| Web Browsers | ✅ | Navigation history |
| E-Library | ✅ | Undo return/borrow actions |
| Photo Editing | ✅ | Undo & Redo operations |
| Text Editors | ✅ | Ctrl+Z / Ctrl+Y history |
| App Navigation | ✅ | Mobile back-stack |

> So this project isn't just theory — it reflects **actual software systems** ✅

---

## 🚀 How to Run
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
javac BrowserHistoryManager_Creative.java
java BrowserHistoryManager_Creative
📚 Technologies Used
Java (JDK 21 recommended)

Swing GUI Framework

Stack & ArrayDeque from Java Collections Framework

📈 Future Enhancements
✔️ Add webpage thumbnails/icons like browsers

✔️ Save & load history from file (persistent memory)

✔️ Keyboard shortcuts for Back/Forward

✔️ URL validation (https://www…)

✔️ Home button + Clear history

🧩 Limitations
No actual internet browsing

Page content is not fetched — only URLs tracked

📂 File Structure
Copy code
BrowserHistoryManager_Creative.java
README.md
🤝 Contribution
Contributions, improvements & suggestions are welcome!

📜 License
MIT License — Free to use for learning and projects ✅

