# WeatherWise: The Dynamic Weather Dashboard

WeatherWise is a sleek, professional weather dashboard built as a single-page application. It provides real-time weather data with a focus on a highly interactive and polished user experience, featuring dynamic animated backgrounds, professional loading skeletons, and a smart, data-aware chatbot.

This project is built with **pure, framework-free JavaScript, HTML, and CSS** to demonstrate core web development skills.

![WeatherWise App Screenshot](https.i.imgur.com/your-screenshot-link.png)
*(**Note:** Please replace the link above with a screenshot of your running application!)*

---

## ✨ Key Features

* **Dynamic Animated Background:** The entire page background is an animated gradient that changes based on the current weather (e.g., clear, rain, clouds).
* **Pro-Level Loading Skeletons:** When fetching data, the app displays a shimmering "skeleton" loading animation, ensuring a smooth and professional user experience.
* **Interactive Forecasts:**
    * The 5-day forecast is fully interactive.
    * **Clicking any day** in the 5-day forecast instantly filters the hourly list to show the specific 3-hour breakdown for that selected day.
* **Precise US EPA AQI:** The app fetches raw PM2.5 data and calculates a "real" **US EPA AQI number** (e.g., "84"), complete with the official color-coding and category (Good, Moderate, etc.).
* **Smart Rule-Based Chatbot:**
    * No AI API needed. The chatbot is 100% rule-based and analyzes the app's live data.
    * It answers context-aware questions like, "What city is this?", "What's the AQI?", or "Do I need an umbrella?".
    * Includes suggested question buttons and a close button.
* **Comprehensive Data:** Provides all key metrics: Feels Like, UV Index, Humidity, Wind Speed, Pressure, Visibility, and Sunrise/Sunset times.
* **Accessible Search:** The city search bar features dropdown suggestions with full keyboard navigation support (Arrow keys and Enter).
* **Polished UI/UX:**
    * Modern "glassmorphism" design for the header, footer, and cards.
    * Subtle "float" animation on the main weather icon.
    * Responsive design for desktop and mobile.

---

## 🚀 How to Run

This project is a single, self-contained HTML file.

1.  **Get an API Key:** Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/) to get your free API key.
2.  **Paste the Key:** Open the `index.html` file in a code editor. Find the `<script>` tag at the bottom and paste your key into the `OPENWEATHERMAP_API_KEY` constant:
    ```javascript
    const OPENWEATHERMAP_API_KEY = "YOUR_API_KEY_HERE";
    ```
3.  **Run:** Simply open the `index.html` file in any modern web browser (like Chrome, Firefox, or Edge).

---

## 🛠️ Technologies Used

* **HTML5:** For the core structure and semantics.
* **CSS3:** For all styling, including the glassmorphism, animated backgrounds, flexbox/grid layouts, and skeleton loading effects.
* **Vanilla JavaScript (ES6+):** For all application logic, including:
    * API fetching with `fetch`.
    * DOM manipulation.
    * State management.
    * Event handling.
    * The smart chatbot logic.
* **Lucide Icons:** For clean and professional icons.
