# sorka.ai landing page

Static landing page for **Sorka** (sorka.ai), built for GitHub Pages.

## Deploy to GitHub Pages

1. **From this repo (sita):**  
   In repo **Settings → Pages**, set **Source** to **Deploy from a branch**, then choose branch (e.g. `main`) and folder **`/github.io`**. Save. The site will be at `https://<username>.github.io/sita/` (or your repo name).

2. **Custom domain (sorka.ai):**  
   In the same Pages settings, set **Custom domain** to `sorka.ai` and follow GitHub’s DNS instructions (CNAME to `username.github.io` or the repo’s Pages URL).

## Edit before publishing

- Replace `your-org/sita` in all GitHub links with your actual repo (e.g. `username/sita`).
- Point the main download button to your releases URL:  
  `https://github.com/your-org/sita/releases`

## Local preview

Open `index.html` in a browser, or use a static server:

```bash
cd github.io && python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
