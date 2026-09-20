# Readly — E-book Landing Page

A polished, responsive landing page for **Readly**, a curated digital bookstore for curious readers. The page pairs editorial typography with a warm, book-inspired visual system to create a calm and inviting browsing experience.

## Preview

The main experience is in [`LeoLabs.html`](./LeoLabs.html).

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Mobile navigation menu with accessible state labels
- Hero section with clear calls to action
- Curated benefits section explaining the Readly experience
- Editorial “Our story” section with a three-step reading journey
- Recent arrivals grid with Fiction, Non-fiction, and All books filters
- Contact form with required fields and inline success feedback
- Automatic copyright year in the footer
- Semantic HTML, descriptive labels, and keyboard-friendly controls

## Built with

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: [DM Sans](https://fonts.google.com/specimen/DM+Sans) and [Playfair Display](https://fonts.google.com/specimen/Playfair+Display)

## Project structure

```text
.
├── LeoLabs.html       # Landing page markup
├── LeoLabs.css        # Layout, responsive styles, and visual design
├── LeoLabs.js         # Navigation, filters, form feedback, and footer year
└── README.md          # Project documentation
```

The repository also contains other standalone HTML experiments. The files listed above make up the Readly e-book landing page.

## Run locally

No build step or package installation is required.

### Option 1: Open the file

Open [`LeoLabs.html`](./LeoLabs.html) directly in a modern browser.

### Option 2: Use a local server

Serving the project locally is recommended because it mirrors static hosting more closely:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000/LeoLabs.html](http://localhost:8000/LeoLabs.html).

## Deploy with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch and the `/ (root)` folder, then click **Save**.
5. Open the published site and append `/LeoLabs.html` to the repository URL.

Because this is a static site, GitHub Pages can serve it without a build pipeline.

## Customization

- Update the brand name, copy, and book listings in [`LeoLabs.html`](./LeoLabs.html).
- Adjust colors, spacing, typography, and responsive breakpoints in [`LeoLabs.css`](./LeoLabs.css).
- Connect the contact form to a real form endpoint in [`LeoLabs.js`](./LeoLabs.js) when backend submission is needed. It currently shows a local confirmation message and does not send data.
- Replace the placeholder email address in the contact section before publishing.

## License

No license has been specified for this project yet. Add a license before distributing or reusing the code publicly.
