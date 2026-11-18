# New Year Countdown

A responsive, real-time countdown timer web application built with vanilla HTML, CSS, and JavaScript that tracks the remaining days, hours, minutes, and seconds until the New Year[cite: 8].

## Preview

<img width="1917" height="866" alt="Screenshot 2026-11-18 153855" src="https://github.com/user-attachments/assets/e144978a-5860-4410-b35c-c87814fad5d1" />

## Features

* **Real-Time Live Countdown:** Computes the exact time gap dynamically down to the second using JavaScript `Date` objects and recursive `setTimeout` loops.
* **Structured Time Units:** Breaks down remaining time into clearly labeled units: Days, Hours, Minutes, and Seconds[cite: 8].
* **Sleek Aesthetic Design:** Features a slateblue full-viewport layout, uppercase tracking headers, large typography, and pseudo-element (`::before`) label generation[cite: 8].

---

## Project Structure

```text
├── index.html      # Main HTML structure with countdown display containers
├── style.css       # Slateblue theme, flexbox centering, and pseudo-element styling
├── index.js        # Date calculation logic, time conversion math, and recursive timer
└── preview.png     # Application screenshot for the README
