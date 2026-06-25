# Codeforces Analytics Dashboard 🚀

A lightweight, high-performance client-side web application designed to track, analyze, and visualize competitive programming metrics in real-time. By interfacing directly with the official Codeforces REST API, this dashboard transforms raw JSON submission data into actionable insights for algorithmic training.

## 📌 Architecture & Tech Stack

This project was intentionally built without heavy frontend frameworks to demonstrate core web fundamentals, asynchronous data handling, and direct DOM manipulation.

*   **Frontend UI:** Vanilla HTML5 & CSS3 (Grid/Flexbox for responsive layouts)
*   **Core Logic:** Vanilla JavaScript (ES6+)
*   **Networking:** Fetch API (Asynchronous HTTP requests, Promise handling)
*   **Data Source:** Official Codeforces API (`user.status` and `user.rating` endpoints)

## ⚙️ Core Features

*   **Real-Time Data Fetching:** Asynchronously pulls a user's entire submission history and contest rating changes with zero server-side caching latency.
*   **Algorithmic Tag Parsing:** Iterates through thousands of JSON submission objects to aggregate data structure and algorithm tags (e.g., Dynamic Programming, Graphs, Greedy, Segment Trees).
*   **Performance Visualization:** Dynamically updates the DOM to display topic-wise accuracy, total problems solved, and rating progression without requiring a page reload.
*   **Zero-Dependency Engine:** Runs entirely in the browser. No Node modules, Webpack, or heavy dependencies required. 

## 🛠️ Local Setup & Installation

Since this is a pure client-side application, running it locally is instantaneous.

1. **Clone the repository:**
```bash
   git clone [https://github.com/](https://github.com/)[YOUR_GITHUB_USERNAME]/codeforces-analytics-dashboard.git