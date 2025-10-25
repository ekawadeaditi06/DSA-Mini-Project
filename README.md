# Browser History Manager (Creative GUI)

A Java Swing-based application that simulates **browser history management** using **Stack (Back)** and **Deque (Forward)** data structures.  
It features an interactive GUI with enhanced visualization of back and forward navigation trails.

---

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Technology Stack](#technology-stack)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Implementation Details](#implementation-details)
- [Contributing](#contributing)
- [License](#license)

---

## Features
- Back and Forward navigation using **Stack (LIFO)** and **Deque (FIFO)**.
- Custom **dark-themed GUI** with clear visualization of history trails.
- **Interactive URL input** for visiting new pages.
- Highlights the **next navigable pages** in the history trails.
- Scrollable panels for long history logs.
- Dynamic display of **Back Stack** and **Forward Deque**.

---

## Screenshots

*Add your screenshots inside a `screenshots/` folder in your repo.*

![Main Window](screenshots/main_window.png)  
*Main browser window with current page and navigation buttons.*

![History Panel](screenshots/history_panel.png)  
*Back and Forward history trail visualizations.*

---

## Technology Stack
- **Language:** Java (JDK 21 recommended)
- **GUI Framework:** Swing
- **Data Structures:** Stack, Deque (ArrayDeque)
- **Build Tool:** Any Java IDE or command line (`javac` & `java`)

---

## How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/<your-username>/BrowserHistoryManager_Creative.git
Navigate to the project folder:

bash
Copy code
cd BrowserHistoryManager_Creative
Compile the Java file:

bash
Copy code
javac BrowserHistoryManager_Creative.java
Run the application:

bash
Copy code
java BrowserHistoryManager_Creative
Make sure your system has JDK installed and javac is accessible in your PATH.

Usage
Enter a URL in the input field (e.g., google.com) and click VISIT.

Navigate BACK using the back button (Stack – LIFO behavior).

Navigate FORWARD using the forward button (Deque – FIFO behavior).

Observe the dynamically updated history trail panels showing the navigation history.

Implementation Details
Back History: Implemented using java.util.Stack.

Forward History: Implemented using java.util.ArrayDeque.

Current Page: Displayed in a non-editable text field with a highlight.

GUI Styling: Custom colors for back, forward, and visit actions.

History Panels: Scrollable JScrollPane with items highlighted to show the next pop/visit action.

Contributing
Contributions are welcome!

Fork the repository.

Create a feature branch:

bash
Copy code
git checkout -b feature/YourFeature
Commit your changes:

bash
Copy code
git commit -m "Add new feature"
Push to the branch:

bash
Copy code
git push origin feature/YourFeature
Open a Pull Request.

License
This project is open-source and available under the MIT License.
See LICENSE for more details.
