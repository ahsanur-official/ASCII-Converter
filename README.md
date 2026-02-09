# ASCII Lab

Modern, responsive ASCII utility with converter tools, a full ASCII table, and bilingual UI support.

## Highlights
- Text to ASCII and ASCII to text
- Binary, hex, and octal conversions (both directions)
- Smart converter with swap, copy, and download
- Light and dark themes
- English and Bangla language toggle

## Screenshots
![Home](ss/Screenshot%20(817).png)
![Converter](ss/Screenshot%20(818).png)
![ASCII Table](ss/Screenshot%20(819).png)

## Pages
- `index.html` - Landing page and quick overview
- `convert.html` - Converter tools
- `table.html` - ASCII table explorer

## Tech Stack
- HTML, CSS, JavaScript (vanilla)
- Google Fonts (Space Grotesk)

## Getting Started
1. Open `index.html` in any modern browser.
2. Use the top navigation to switch between Converter and ASCII Table.

## Usage Guide
### Smart Converter
- Select formats from the `From` and `To` dropdowns.
- Use **Swap** to flip formats quickly.
- Click **Convert** to generate output.
- Use **Copy** to copy output to clipboard.
- Use **Download** to save output as a text file.

### Quick Panels
- Each panel converts one direction (e.g., Text → ASCII, ASCII → Text).
- Enter input in the top field and click **Convert**.

### ASCII Table
- Use the search bar to filter by character or code.
- Use the range selector to switch between all codes and printable-only codes.

## Input Format Tips
- ASCII/Hex/Octal input accepts comma, space, or new-line separated numbers.
- Binary input expects 8-bit blocks (e.g., `01000001`).
- Hex input may include `0x` prefixes; they are handled automatically.

## Theming and Language
- Use the **Dark mode** button to toggle themes.
- Use **বাংলা** or **EN** to switch the language.

## Run Locally
Option A: Open the file directly
1. Double-click `index.html`.

Option B: Serve with a simple local server
1. Use any static server (VS Code Live Server, Python, or Node).
2. Example (Python): `python -m http.server 5500`
3. Visit `http://localhost:5500`.

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/my-change`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to your branch: `git push origin feature/my-change`.
5. Open a pull request with a clear description.

## Roadmap Ideas
- Add copy buttons per row in the ASCII table.
- Export table data to CSV.
- Add UTF-8 or extended ASCII reference.

## Project Structure
- `app.js` - UI logic, translations, and converters
- `styles.css` - Styling and layout
- `ss/` - Screenshots used in README

## License
All rights reserved.
