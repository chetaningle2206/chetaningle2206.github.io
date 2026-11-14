# Chetan Ingle — Portfolio Website

A responsive, static portfolio website built with **HTML5, CSS3, and vanilla JavaScript**. It is designed for free deployment on GitHub Pages.

## Project structure

```text
chetan-portfolio-starter/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── favicon.svg
    └── Chetan-Ingle-Resume.pdf
```

## Run locally

No build tools or package installation are required.

1. Extract this folder.
2. Open `index.html` in a browser.
3. For a local development server, open a terminal in this folder and run:

   ```bash
   py -m http.server 5500
   ```

4. Visit `http://localhost:5500`.

## Free deployment with GitHub Pages

1. Sign in to GitHub and create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io` (replace the placeholder with your GitHub username).
2. Upload the contents of this folder to the root of that repository. `index.html` must be at the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for the Pages deployment to complete. Your site URL will be `https://YOUR-GITHUB-USERNAME.github.io/`.

GitHub Pages on GitHub Free requires a public repository. Everything in the repository and the published site is public, including the résumé PDF. Review the résumé for personal details before publishing.

## Personal details to verify before publishing

- Confirm the LinkedIn URL in `index.html` (`https://www.linkedin.com/in/chetan-ingle/`).
- Add your GitHub profile link once you confirm the exact URL; it is intentionally not guessed here.
- Angular appears in the uploaded résumé, but it is not highlighted in the portfolio. Add it only when you are comfortable describing your hands-on experience with it.
- The impact metrics are copied from the résumé. Be ready to explain how each was measured and your contribution to it.
- Add a second project only when you have a real, presentable project and can describe your own contribution.
- Do not publish employer code, internal screenshots, real employee data, credentials, API keys, or confidential business information.

## Updating content

Edit `index.html` to update profile copy, skills, experience, links, or metrics. Replace `assets/Chetan-Ingle-Resume.pdf` with your latest approved résumé PDF, keeping the same file name so the download buttons continue to work.

## Notes

- No backend, database, paid domain, or third-party JavaScript package is required.
- The Google Fonts stylesheet is an optional external enhancement. The page falls back to system sans-serif fonts if it cannot load.
- A GitHub Pages URL (`.github.io`) is free. A custom domain such as `chetaningle.com` generally requires purchasing the domain separately.
