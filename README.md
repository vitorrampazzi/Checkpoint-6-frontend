# MatrixShop — Frontend Checkpoint 06

An academic storefront layout built with HTML and Tailwind CSS. The page presents a fashion collection, an outlet product grid, and a featured product section.

## What the project demonstrates

- Responsive layouts using Tailwind breakpoints.
- Grid and flexbox composition.
- In-page navigation between collection, outlet, and featured product sections.
- Product imagery, typography, hover styles, and icon integration.

The shopping cart, login, and wishlist links are visual placeholders. The project does not include a backend, checkout, or account system.

## Technology

- HTML
- Tailwind CSS 3
- Google Fonts
- Font Awesome

## Repository structure

```text
src/
├── assets/images/
├── index.html
└── input.css
dist/
└── output.css
tailwind.config.js
package.json
participantes.txt
```

## View locally

Clone the repository:

```bash
git clone https://github.com/vitorrampazzi/Checkpoint-6-frontend.git
cd Checkpoint-6-frontend
```

Open `src/index.html` in a browser. The page loads its generated stylesheet from `dist/output.css`.

### Update the styles

To rebuild the Tailwind stylesheet while editing, install Node.js and npm, then run:

```bash
npm install
npm run dev
```

The `dev` script watches `src/input.css` and writes the generated CSS to `dist/output.css`; it does not start a web server.

## Contributors

| Name | Student ID |
| --- | --- |
| Vitor Rampazzi Franco | 562270 |
| Daniel Brito | 566236 |
| Gustavo Borsato | 564621 |
