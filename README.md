# Chethan E · Portfolio

Personal portfolio of **Chethan E**, aspiring data scientist and MCA Data Science student in Bengaluru.
Retro-brutalist design with five pages: Home, Projects, Skills, Experience and Contact.

- GitHub: https://github.com/echethan8-byte
- LinkedIn: https://www.linkedin.com/in/chethan-e-033a94253

## Files

| File | What it is |
|------|------------|
| `index.html` | The whole site (HTML, CSS and JavaScript in one file) |
| `Chethan_E_Resume.pdf` | Resume opened by the "Open resume" buttons |
| `favicon.svg` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

No build step and no install. Open `index.html` in a browser to view it.

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `portfolio`
   (or `echethan8-byte.github.io` to get the address `https://echethan8-byte.github.io`).
2. Upload all the files in this folder to the repository, including `.nojekyll`.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. After a minute or two the site is live at `https://echethan8-byte.github.io/portfolio/`.

## Page links

Each page has its own link: `#home`, `#projects`, `#skills`, `#experience`, `#contact`
(for example `https://echethan8-byte.github.io/portfolio/#projects`).
On a computer, the ← and → arrow keys move between pages.

## Updating

- **Resume:** replace `Chethan_E_Resume.pdf` with a new file of the same name.
- **Text:** edit `index.html`. Each page is a `<section class="view" data-view="...">` block.
- **Colours:** change the values at the top of the `<style>` block (`--accent` is the orange).
