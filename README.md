# Build a Website Design System

A static, single-page website style guide built with plain HTML and CSS. It documents a small design system, a color palette with intended usage, font samples, and typography specifications for headings and body text, so a website's visual language is defined in one place.

## Motivation

This project was created as a learning exercise in building a design system: deciding on a consistent set of colors, fonts and type styles before building a website, and presenting them as a reference page.

## Features

- **Color palette** - three color swatches with name, hex code and intended usage:
  - Walnut Brown `#5C5346` - footer
  - Desert Sand `#E4BB97` - typography
  - Pigment Green `#1F9D53` - buttons
- **Font samples** - Courier New (monospace) and Verdana (sans-serif), each shown in italic, bold and regular
- **Typography specifications** - font weight, size and family for `h1`, `h2` and `p`
- **Hover effect** - words in the page title turn italic on hover

## Tech/framework used

**Built with:**

- HTML5
- CSS3

## Code style

No linters or formatters (ESLint, Prettier, Stylelint, EditorConfig) are configured. Commit messages follow the [Conventional Commits](https://www.conventionalcommits.org/) specification.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hevolx/Build-a-Website-Design-System.git
   cd Build-a-Website-Design-System
   ```

2. No dependencies, environment configuration or database are required.
3. Open `index.html` in a web browser, or serve the folder with any static file server, for example:

   ```bash
   python3 -m http.server 8000
   ```

   and visit <http://localhost:8000>.

## Usage examples

1. Open `index.html` in a browser.
2. Hover over the words in the **Website Style Guide** heading to see them switch to italic.
3. Use the **Color** section to look up the hex code and purpose of each brand color.
4. Compare the **Fonts** samples to see how Courier New and Verdana render in italic, bold and regular.
5. Refer to the **Typography** section for the weight, size and font family to use for `h1`, `h2` and paragraph text.
