# Metal Catalyst Surface Model

An interactive, single-page browser simulation that explains how a metal catalyst surface helps exhaust molecules adsorb, react, desorb, and leave the catalyst ready for another cycle.

## Use locally

Open `index.html` directly in a browser, or serve the folder with a tiny static server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000/>.

## Host on GitHub Pages

1. Push this repository to GitHub.
2. In the repository, open **Settings** → **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you pushed and the repository root (`/`) as the folder.
5. Save. GitHub Pages will publish `index.html` as the site home page.

## Project structure

- `index.html` — the page GitHub Pages will load by default.
- `catalyst_surface_atomic_model.html` — the original standalone HTML simulation file.

No build step or package installation is required.
