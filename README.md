# Royal Intelligence: Pressure Performers Dashboard

A static, single-page dashboard for SupeRR Selector Season 2, Round 1. It ranks the IPL and T20I batters and bowlers who perform best under pressure, using a leverage-based pressure index.

## Deploy on GitHub Pages
1. Push `index.html`, `README.md`, `.nojekyll` and the `data/` folder to the root of a repository.
2. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repo>/`.

The data is embedded in `index.html`, so the page works on its own. D3 v7.9.0 and the Google Fonts load from CDNs. The `data/*.csv` files are the same tables, provided for download.
