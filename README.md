⏰ Analog Clock

📌 Project Overview

A real-time Analog Clock developed using HTML, CSS, and JavaScript. This project displays the current local time with rotating hour, minute, and second hands, along with a digital time display in 12-hour format with AM/PM.

The clock features a modern dark-themed interface with smooth styling and dynamically generated clock markings.

✨ Features

- Real-time clock functionality.
- Hour, minute, and second hand rotation.
- 60 dynamically generated tick marks.
- Automatic positioning of numbers from 1 to 12.
- Digital time display with AM/PM.
- Modern dark-themed UI.
- Responsive positioning using CSS Flexbox.

🛠️ Technologies Used

- HTML5 – Webpage structure.
- CSS3 – Styling, layout, shadows, and visual effects.
- JavaScript – Time calculations, DOM manipulation, and clock functionality.

⚙️ Working Principle

1. HTML creates the clock structure and its components.
2. CSS styles the clock and positions its elements.
3. JavaScript generates 60 tick marks and 12 clock numbers.
4. The "Date()" object retrieves the current system time.
5. Mathematical calculations determine the rotation angles of the clock hands.
6. "setInterval()" updates the clock every second.

📐 Clock Hand Calculation

- Hour Hand: "((h % 12) + m / 60) * 30"
- Minute Hand: "(m + s / 60) * 6"
- Second Hand: "s * 6"

🚀 How to Run the Project

1. Clone this repository:
   git clone YOUR_REPOSITORY_URL
2. Open the project folder.
3. Open "index.html" in your web browser.
4. The analog clock will automatically display your current local time.

📂 Project Structure

Analog-Clock/
│
├── index.html
└── README.md

🎯 Learning Outcomes

- Understanding HTML structure and CSS styling.
- Practicing JavaScript fundamentals.
- Learning DOM manipulation.
- Applying mathematical calculations in programming.
- Understanding CSS positioning and transformations.
- Working with JavaScript Date and setInterval functions.

👩‍💻 Developer

Akila Sakthivel S
BE Electronics and Communication Engineering

---

⭐ If you find this project interesting, feel free to explore the repository!