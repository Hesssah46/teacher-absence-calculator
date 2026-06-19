# teacher-absence-calculator
A smart web-based absence rate calculator for educational institutions and schools, tailored for the Saudi academic year 1447 with dynamic, actual working days calculation.

# Smart Absence Rate Calculator (1447 AH) 🗓️

An intuitive and elegant web application designed for Saudi schools and educational institutions to accurately calculate monthly absence percentages for teachers and staff. The calculator automatically adjusts based on the official actual working days for each Hijri month across the academic year 1447-1448 AH.

## 🚀 Live Demo
You can access and test the live application here: [guileless-melomakarona-c7ab07.netlify.app](https://6a07a404391b57e0945e8b67--guileless-melomakarona-c7ab07.netlify.app/)

## ✨ Key Features
* **📅 Dynamic Hijri Calendar Data:** Pre-loaded with official actual working days for each month of the 1447/1448 AH school year.
* **📊 Smart Aggregate Calculations:** Computes absence rates globally based on total actual working days relative to the employee headcount ($Total\ Days = Working\ Days \times Employees$).
* **🚦 Visual Status Indicators:** Dynamically rates the absence percentages into three colored categories:
  * **Green (Excellent):** Normal rate ($\le 5\%$).
  * **Orange (Acceptable):** Moderate rate ($5\% < \text{rate} \le 12\%$).
  * **Red (Alert):** High absence rate ($> 12\%$).
* **🎨 Premium UI/UX:** Clean, responsive card layout featuring elegant typography (Tajawal font) and smooth micro-interactions.

## 🛠️ Tech Stack
* **Structure & UI Design:** HTML5 & Premium Custom CSS Properties (Variables)
* **Core Logic & Reactivity:** Vanilla JavaScript (Event-driven calculation updates)
* **Hosting Platform:** Netlify

## 📂 Project Structure
Your repository contains the lightweight single-page application structure:
├── index.html       # Contains the responsive layout, premium styling, and core calculator logic
