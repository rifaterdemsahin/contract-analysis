# Agent Guidelines & Memory — contract-analysis

This repository contains an interactive dashboard analyzing career and contract history data extracted from Excel.

## 🛠 Project Structure

- `index.html`: The main dashboard page with all visualizations, filtering logic, and timeline layout.
- `index.css`: Vanilla CSS stylesheet specifying typography, dark/light theme tokens, and layout.
- `data.js`: Cleaned contract and milestone data exported from the original Excel source.
- `Erdem Income _ Roadmap ( past authoring on a report reality card ).xlsx`: Source spreadsheet.

## 🧠 Workflows & Automation

### Post-Task Validation

Whenever making modifications to pages or configurations:
1. Run a quick check or build verification (e.g. check for markup validity, parse errors).
2. Start a local server to test (such as `python3 -m http.server 8000` or equivalent).
3. Open `index.html` in the default browser to verify aesthetics, responsiveness, and interactive elements.

### Commit and Push Guidelines
- Ensure all source files and exports are committed.
- Write descriptive commit messages.
- Always push to the remote repository.
