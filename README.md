# EditorMarkdownWeb
#### Bocaletto Luca

A lightweight, single-page Markdown editor featuring split-view live preview, theme toggle, auto-save, and export capabilities. Fully static—no server required—and optimized for SEO and sharing.

---

## Table of Contents

- [Features](#features)  
- [Demo](#demo)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  
- [Author](#author)  

---

## Features

- Split-view editor with side-by-side Markdown input and HTML preview  
- Light/Dark theme toggle, persisted across sessions  
- Automatic draft saving via `localStorage`  
- Export current document as `.md` or standalone `.html`  
- Fully static: no backend or build step required  
- SEO meta tags (Open Graph, Twitter Card, keywords, description)  
- Sticky header and responsive layout for desktop and mobile  

---

## Demo

A live demo is available on GitHub Pages:  
https://bocaletto-luca.github.io/EditorMarkdownWeb

---

## Tech Stack

- HTML5 for semantic markup  
- CSS3 with responsive Flexbox and CSS variables  
- Vanilla JavaScript for DOM manipulation and state management  
- [Showdown.js](https://github.com/showdownjs/showdown) for Markdown-to-HTML conversion  

---

## Installation

```bash
git clone https://github.com/bocaletto-luca/EditorMarkdownWeb.git
cd EditorMarkdownWeb
```

No additional dependencies are required. The editor runs in any modern browser.

---

## Usage

1. Open `index.html` directly in a browser, or serve via a static file server:  
   ```bash
   # Python 3 built-in HTTP server
   python3 -m http.server 8000
   ```
2. Navigate to `http://localhost:8000/index.html`.  
3. Begin typing Markdown on the left; the rendered HTML appears in real time on the right.  
4. Use the header controls to:
   - Export as `.md`  
   - Export as standalone `.html`  
   - Toggle between light and dark themes  

All drafts and theme preferences are saved automatically in the browser’s `localStorage`.

---

## Project Structure

```text
EditorMarkdownWeb/
├── index.html       # Single-page Markdown editor
└── README.md        # Project documentation
```

---

## Contributing

Contributions are welcome under the following guidelines:

- Fork the repository and create a feature branch (`git checkout -b feature/xyz`)  
- Commit changes with clear, descriptive messages  
- Submit a pull request against `main`  
- Ensure code adheres to existing style and passes linting (if added)  

---

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

---

## Author

Bocaletto Luca  
GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)
