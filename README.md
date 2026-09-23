# ⏰ Digital Clock

A simple and responsive **Digital Clock Web Application** built using HTML5, CSS3, and JavaScript. The clock displays the current time in **HH:MM:SS** format and updates automatically every second.

## 📌 Project Overview

This project was created to practice fundamental JavaScript concepts such as:

* JavaScript `Date` object
* `setInterval()` timer
* DOM selection and manipulation
* Dynamic content updates
* String formatting with `padStart()`
* Responsive web design

## ✨ Features

* 🕐 Displays current hours, minutes, and seconds
* 🔄 Automatically updates every second
* `HH:MM:SS` time format
* 🔢 Adds leading zeros to single-digit values
* 📱 Responsive design
* 🎨 Simple and clean user interface

## 🛠️ Technologies Used

* **HTML5** – Page structure
* **CSS3** – Styling and responsive layout
* **JavaScript** – Clock functionality and real-time updates

## 📂 Project Structure

```text
digital-clock/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ How It Works

The application uses JavaScript's `Date` object to get the current system time.

```javascript
const now = new Date();

const hours = String(now.getHours()).padStart(2, "0");
const minutes = String(now.getMinutes()).padStart(2, "0");
const seconds = String(now.getSeconds()).padStart(2, "0");
```

The time is displayed on the webpage using DOM manipulation:

```javascript
document.getElementById("clock").textContent =
    `${hours}:${minutes}:${seconds}`;
```

The clock updates automatically every second using:

```javascript
setInterval(updateClock, 1000);
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/digital-clock.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

That's it! 🎉

## 📸 Output

The application displays a live digital clock:

```text
Digital Clock

20:37:25

Current Time
```

## 🎯 Learning Outcome

Through this project, I gained practical experience in:

* Working with JavaScript Date objects
* Using timers with `setInterval()`
* Manipulating HTML elements using JavaScript
* Formatting dynamic data
* Creating responsive web interfaces

## 🔮 Future Enhancements

* Add 12-hour / 24-hour format
* Add current date and day
* Add alarm functionality
* Add dark/light mode
* Add multiple world time zones

## 👨‍💻 Author

**Selvakumar P**

Computer Science Engineering Student

