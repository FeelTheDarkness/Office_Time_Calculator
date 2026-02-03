## Office Hours Calculator

A sleek, web-based tool designed to help office professionals track their daily working hours, calculate current averages, and determine exactly when they can leave to hit their targets. This tool uses a specific "office format" (e.g., `8.15` for 8 hours and 15 minutes) to match common corporate reporting systems.

---

### 🚀 Features

* **Average Tracking**: Calculate your current net working hours average based on total hours and days present.
* **Departure Planning**: Input your arrival time and desired daily average to get an exact "Leave By" time.
* **Projected Average**: A dedicated calculator to see how a specific departure time today will affect your overall monthly average.
* **Fixed Lunch Logic**: Automatically accounts for a fixed 30-minute lunch break in all calculations.
* **Responsive Design**: Modern, mobile-friendly UI with a professional gradient aesthetic and real-time clock.

---

### 🛠️ How to Use

1. **Report Data**: Enter your **Total Net Hours**, **Total Lunch Hours**, and **Present Days** directly from your HR or tracking report.
2. **Today's Arrival**: Enter the time you clocked in today (e.g., `9:30 AM`).
3. **Set a Target**: Enter your **Desired Average** (e.g., `8.30`) to see what you need to do today to stay on track.
4. **Calculate**: Click **Calculate Required Hours** to see your "Leave By" time.
5. **What If?**: Use the **Projected Average** section to test different departure times (e.g., "If I leave at 6:00 PM, what will my average be?").

---

### 💻 Technical Details

* **Frontend**: HTML5, CSS3 (Flexbox/Grid), and FontAwesome icons.
* **Logic**: Pure JavaScript (ES6+) with zero dependencies.
* **Time Formatting**: Includes custom functions to handle the conversion between "Office Format" (`Hours.Minutes`) and standard integer minutes to ensure mathematical accuracy.

---

### 📥 Installation

Since this is a standalone client-side application, no installation is required:

1. Download the `calculator.html` file.
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3. (Optional) Host it on **GitHub Pages** for easy access on your mobile device while at the office.

---

### 📝 Note on Time Formats

This calculator uses the `H.MM` format:

* `8.05` = 8 Hours, 5 Minutes
* `8.50` = 8 Hours, 50 Minutes
* **Note**: `8.5` is treated as an invalid format to prevent confusion between "5 minutes" and "50 minutes." Always use two digits for minutes.
