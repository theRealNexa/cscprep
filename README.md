# cscprep 🎓

A robust, laboratory-style quiz platform designed for computer science students to practice, test, and master concepts across five core courses. 

## 🚀 Live Application
Test your knowledge here: [cscprep.vercel.app](https://vercel.app)

## 📚 Covered Courses
The platform includes comprehensive question banks and mock assessments for the following five specialized courses:
* **CSC 208** – Introduction to Computer Hardware
* **CSC 226** – Object-Oriented Programming (OOP)
* **CSC 218** – Sequential Programming
* **CSC 214** – Databases
* **IFT 212** – Information Technology Architecture
* **To be updated.**
Course codes and titles are based on **Lagos State University** Course Handbook.

## ✨ Interface & User Experience (UX)
* **Course Selector:** A sticky top navigation bar allowing students to instantly switch between the five subjects.
* **Live Performance Tracker:** Real-time stats bar tracking dynamic **Score**, **Answered** count, and **Accuracy (%)** metrics as you work.
* **Topic Filtering:** Granular search filters to narrow down questions within specific modules of a course.
* **Fluid Navigation:** Intuitive **Previous/Next** controls paired with an active `"X of Y answered"` status tracker.
* **Session Controls:** A global **Reset** button to wipe current scores, clear storage, and start fresh.

## 🛠️ Under the Hood
* **Single-File Architecture:** Lightweight standalone HTML builds per course for speed and self-contained logic.
* **Persistent Progress:** Built-in `localStorage` integration ensures score tracking and answered statuses survive page refreshes or closed browser sessions.
* **Data Management:** Extensible question banks organized natively in structured JavaScript arrays.

## 📦 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/theRealNexa/cscprep
   ```
2. Open the directory and launch any course file (e.g., `index.html`) directly in your favorite modern web browser.

## 📄 License
This project is licensed under the MIT License.
