# Keyboard Heatmap Visualizer

A real-time keyboard usage visualizer that tracks how you type and displays a dynamic heatmap directly in the browser.

This project captures keystrokes, calculates live typing statistics, and visually highlights frequently used keys. It is fully client-side and requires no backend or external libraries.

---

## Overview

Keyboard Heatmap Visualizer is a single-page web application that:

- Tracks every key pressed during a session
- Displays a live keyboard heatmap
- Calculates typing statistics, including WPM
- Allows exporting session data as JSON
- Runs entirely in the browser

All functionality is contained in a single HTML file.

---

## Tech Stack

- HTML5  
- CSS3  
- Vanilla JavaScript (ES6+)  
- Browser Keyboard Event API  
- Blob API for exporting data  

---

## Features

### Real-Time Heatmap

Keys dynamically change color based on relative usage intensity:

- Low usage → Blue  
- Medium usage → Orange  
- High usage → Red  

Color intensity is calculated relative to the most frequently pressed key in the current session.

### Live Statistics

- Total key presses  
- Unique keys used  
- Most pressed key  
- Words per minute (WPM)

### Controls

- Reset session data  
- Toggle heatmap on or off  
- Export session data as JSON

---

## Project Structure

```text
keyboard_heatmap.html
README.md
```

All HTML, CSS, and JavaScript logic is contained within:

```text
keyboard_heatmap.html
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/keyboard-heatmap.git
```

2. Open `keyboard_heatmap.html` in your browser.

No installation or dependencies are required.

---

## License

Open source. Free to use and modify.
