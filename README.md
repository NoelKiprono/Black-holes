# 🌌 Space Explorer — Black Holes

A space-themed educational webpage about black holes, built with **HTML5** and **CSS3**. The page introduces what black holes are, outlines their main types, explains the event horizon, and shares a few interesting facts in a dark, astronomy-inspired layout.

## ✨ Features

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

## 🛠️ Built With

- **HTML5** — page structure and content
- **CSS3** — layout, colors, typography, backgrounds, and responsive styling
- **CSS Grid and Flexbox** — page layout and navigation

No JavaScript or build tools are required for the page as currently written.

## 📁 Project Structure

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

## 🚀 Getting Started

### 1. Clone or download the repository

If the project is hosted on GitHub, clone it with:

```bash
git clone <repository-url>
cd <repository-folder>
```

Replace the placeholders with your repository URL and folder name.

### 2. Check the files and image assets

Make sure `Black-holes.html`, `styles.css`, and the referenced images are in the expected locations.

### 3. Open the webpage

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

## 🎨 Design Overview

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

## 🧭 Page Content

1. **Introduction** — what a black hole is and how one can form.
2. **Types of Black Holes** — stellar, supermassive, and intermediate black holes.
3. **Event Horizon** — the boundary beyond which matter and light cannot escape.
4. **Fun Facts** — time effects, growth by absorbing matter, and supermassive black holes in galaxies.

## 🔧 Customization

- **Change colors:** edit the CSS variables near the top of `styles.css`.
- **Change the page content:** edit the headings, paragraphs, and lists in `Black-holes.html`.
- **Replace the images:** update the image files or their paths in the HTML and CSS.
- **Adjust the layout:** edit the `.layout`, `.content-grid`, and responsive media-query rules in `styles.css`.
- **Add more pages:** create the linked pages and reuse the shared stylesheet and layout classes.

## ⚠️ Notes

- The stylesheet references image assets that must be present for the intended visual design.
- The navigation includes links to other Space Explorer pages that are not part of the two uploaded files.
- The HTML filename is `Black-holes.html`, while its navigation link points to `blackholes.html`. On case-sensitive systems, filenames and links must match exactly. Update the link or rename the file to make navigation consistent.
- The current layout uses `height: 100vh`; on smaller screens or with longer content, consider testing the page for overflow and adjusting the layout if needed.

## 🗺️ Roadmap Ideas

Possible future improvements:

- Add working topic links that jump to each section.
- Add descriptive captions or credits for astronomy images.
- Improve keyboard focus styles and accessibility.
- Add more detailed content and reliable references about black holes.
- Build the linked Home, Planets, Stars, and Gallery pages using the shared CSS layout.

## 📄 License

No license was provided with the uploaded files. If you plan to share or accept contributions to this project publicly, add a `LICENSE` file specifying how others may use, modify, and distribute the code.

---

**Space Explorer — Discover the universe, one topic at a time.**
