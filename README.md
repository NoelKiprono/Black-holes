Space Explorer — Black Holes

A space-themed educational webpage about black holes, built with **HTML5** and **CSS3**. The page introduces what black holes are, outlines their main types, explains the event horizon, and shares a few interesting facts in a dark, astronomy-inspired layout.
Features

- **Space-themed design** with a dark background and light text.
- **Navigation bar** with links to Home, Planets, Stars, Black Holes, and Gallery pages.
- **Topics sidebar** listing the main subjects covered on the page.
- **Black hole introduction** explaining their strong gravity and formation from massive stars.
- **Types of black holes**:
  - Stellar black holes
  - Supermassive black holes
  - Intermediate black holes
- **Event horizon section** describing the boundary beyond which escape is impossible.
- **Fun facts** about time, matter absorption, and black holes at the centers of galaxies.
- **Responsive layout** that switches to a single-column content layout on narrower screens.
- **Reusable CSS layout** intended to support other pages in the Space Explorer site.

 Built With

- **HTML5** — page structure and content
- **CSS3** — layout, colors, typography, backgrounds, and responsive styling
- **CSS Grid and Flexbox** — page layout and navigation

No JavaScript or build tools are required for the page as currently written.
 Project Structure

```text
repository/
├── Black-holes.html
├── styles.css
└── images/
    ├── blackhole.png
    └── blackhole header image.png
```

The HTML also links to `index.html`, `planets.html`, `stars.html`, and `gallery.html`. Those pages are not included in the uploaded files, so add them to the repository if you want those navigation links to open working pages.

**Important:** Keep the image files in the `images/` directory and preserve the filenames exactly, including the spaces in `blackhole header image.png`, or update the paths in the HTML/CSS accordingly.

Getting Started

 1. Clone or download the repository

If the project is hosted on GitHub, clone it with:

```bash
git clone <repository-url>
cd <repository-folder>
```

Replace the placeholders with your repository URL and folder name.

### 2. Check the files and image assets

Make sure `Black-holes.html`, `styles.css`, and the referenced images are in the expected locations.
 3. Open the webpage

Open `Black-holes.html` in a web browser.

Alternatively, use a local development server from the project directory:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/Black-holes.html
```

Stop the server with `Ctrl+C` when you are finished.

 Design Overview

The stylesheet defines a small set of CSS custom properties for the page's color theme:

| Variable | Purpose |
|---|---|
| `--bg-dark` | Main dark background |
| `--primary` | Blue primary color |
| `--secondary` | Sidebar background |
| `--text-light` | Main light text color |
| `--accent` | Accent color used for headings and hover states |

The page uses a shared grid with a header, sidebar, main content area, and footer. Within the main content, another grid places the black hole image beside the explanatory text. At viewport widths of **768px or less**, the layout changes to a single-column arrangement and the navigation stacks vertically.

The stylesheet also contains a page-specific header background using `images/blackhole header image.png`.
 Page Content

1. **Introduction** — what a black hole is and how one can form.
2. **Types of Black Holes** — stellar, supermassive, and intermediate black holes.
3. **Event Horizon** — the boundary beyond which matter and light cannot escape.
4. **Fun Facts** — time effects, growth by absorbing matter, and supermassive black holes in galaxies.

