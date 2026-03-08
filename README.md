# Text-Based Data Chart Generator

Text-Based Data Chart Generator is a lightweight collection of pure HTML/CSS/JavaScript experiments that turn plain text input into simple, data-driven charts directly in the browser. Each HTML file in this repo is a self-contained prototype exploring different ways to go from raw text to visual charts without any build tools, frameworks, or backend.

## Features

- Convert plain text or CSV-style input into visual charts in the browser.
- Multiple standalone demos (`text-based data chart generator 0.html` – `7.html`) to test different layouts and interactions.
- Pure front-end: no dependencies, no bundlers, no external APIs.
- Easy to tweak and extend for your own projects, tutorials, or code samples.

## Getting Started

### Prerequisites

You only need a modern web browser (Chrome, Firefox, Edge, Safari).  
No installs, no build steps, no backend.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/endritngjelina/Text-Based-Data-Chart-Generator.git
   cd Text-Based-Data-Chart-Generator
   
2. Open any of the demo files in your browser:

text-based data chart generator 0.html

text-based data chart generator 1.html

...

text-based data chart generator 7.html

You can simply double-click a file, or start a local server:

# Python 3
python -m http.server 8000
# Then open http://localhost:8000 in your browser

How It Works (Concept)
Each demo file:

Accepts text-based data (for example: labels and values separated by commas or new lines).

Parses this text using vanilla JavaScript.

Maps the parsed data into a simple chart representation (bars, lines, etc.) using HTML/CSS.

This design keeps everything transparent and beginner-friendly, making it good for learning, experimenting, or quickly prototyping text-to-chart ideas.

Folder / File Structure
LICENSE – Project license (MIT).

README.md – Documentation (this file).

text-based data chart generator 0.html – Base prototype.

text-based data chart generator 1.html – Variant/iteration 1.

text-based data chart generator 2.html – Variant/iteration 2.

text-based data chart generator 3.html – Variant/iteration 3.

text-based data chart generator 4.html – Variant/iteration 4.

text-based data chart generator 5.html – Variant/iteration 5.

text-based data chart generator 6.html – Variant/iteration 6.

text-based data chart generator 7.html – Latest iteration / experimental version.

Note: Each HTML file is intentionally self-contained so you can copy-paste or modify individual versions without breaking others.

Use Cases
Quick prototypes for text-to-chart interfaces.

Teaching examples for HTML/CSS/JavaScript data visualization.

Sandbox for experimenting with parsing text input into structured data.

Inspiration for integrating text-based chart generation into larger apps.

Roadmap / Ideas
Add screenshots or GIFs of each version.

Standardize the input format and UI across all demos.

Add support for more chart types (pie, line, stacked bar, etc.).

Optional: integrate with an API-based chart renderer (e.g., QuickChart, ECharts) while keeping the text-driven workflow.

Contributing
Contributions, ideas, and refactors are welcome:

Fork the repo.

Create a feature branch:
git checkout -b feature/my-improvement

3. Commit your changes and open a pull request.

Even small improvements (styling tweaks, better parsing, bug fixes) are appreciated.

License
This project is licensed under the MIT License. See the LICENSE file for details.


***
