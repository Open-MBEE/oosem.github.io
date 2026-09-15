# oosem.github.io

Static site for the Object-Oriented Systems Engineering Method (OOSEM) brief,
published with GitHub Pages at <https://oosem.opensysml.org>.

The site is a single `index.html` at the repository root. Every push to `main`
runs `.github/workflows/pages.yml`, which uploads the repository contents as a
Pages artifact and deploys it. `CNAME` pins the custom domain and `.nojekyll`
disables Jekyll processing so the HTML is served as-is.

To preview locally, open `index.html` in a browser or run
`python3 -m http.server` from the repository root.
