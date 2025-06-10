# Portfolio Website

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [License](#license)

---

## Overview

**Portfolio Website** is a modern single-page portfolio site for a developer, designed to showcase skills, experience, projects, and contact information. The project is implemented using HTML, CSS, and JavaScript, with responsive layout and interactive elements.

---

## Features

- 📄 Home page with brief info and photo
- 🧑‍💻 "About Me" section with work experience and education
- 🛠️ "Tech Stack" section with technology icons
- 📂 "Projects" page with filtering by technology, theme, and platform, and card view switching
- 📬 "Contact" page with feedback form
- 🌙 Mobile menu (burger)
- 🔗 Social media links

---

## Technologies

- **HTML5** — page markup
- **CSS3** (SCSS-like structure) — styling, responsiveness, components
- **JavaScript (Vanilla)** — filter logic, menu, DOM interaction
- **Fonts:** [Poppins](fonts/Poppins/) and [DM Sans](fonts/DM_Sans/)
- **SVG/JPG** — icons and images

---

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/your-portfolio.git
   cd your-portfolio
   ```
2. **Open the folder in your editor (e.g., VS Code).**
3. **Run a local server** (for example, using Live Server or any static site server).

---

## Usage

- Open `index.html` in your browser.
- To change content, edit the corresponding HTML files:  
  - `index.html` — home page  
  - `about.html` — about me  
  - `tech-stack.html` — tech stack  
  - `projects.html` — projects  
  - `contact.html` — contacts
- To add projects, edit the `data` array in [`js/projects.js`](js/projects.js).

---

## Project Structure

```
/
├── about.html
├── contact.html
├── index.html
├── projects.html
├── tech-stack.html
├── css/
│   ├── style.css
│   ├── components/
│   └── pages/
├── fonts/
├── img/
│   ├── jpg/
│   └── svg/
├── js/
│   ├── main.js
│   └── projects.js
```

---

## Examples

- **Project Filtering:**  
  On the [projects.html](projects.html) page, you can select technology, theme, or platform to filter projects.
- **Responsiveness:**  
  The site displays correctly on mobile devices.
- **Mobile Menu:**  
  A burger menu appears on smaller screens.

---

## License

This project is distributed under the MIT license.
