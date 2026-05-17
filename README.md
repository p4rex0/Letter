# Letters for you

Plain static site: HTML + CSS only, ready for **GitHub Pages**.

## Edit your content

- **`index.html`** — home page: hero text and the grid of letter cards. Each card is an `<a class="letter-card" href="...">` pointing to a letter page.
- **`letter-1.html`**, **`letter-2.html`** — full letter pages. Copy a file to add `letter-3.html`, update `<title>`, `<time>`, headings and paragraphs, then add a matching card on the index.

There is no JavaScript and nothing is stored in the browser beyond normal browsing.

## Deploy on GitHub Pages

1. Create a repository and push this folder (include `.github` and `.nojekyll` if you use the included workflow).
2. **Settings → Pages → Source: GitHub Actions**.
3. Push to `main` or `master`. After the workflow succeeds, open the Pages URL shown for the repo.

## Local preview

Open `index.html` in a browser, or from this directory:

`npx --yes serve .`

Then open the URL it prints.
