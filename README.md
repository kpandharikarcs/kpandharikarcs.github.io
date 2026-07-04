# Kalyani Pandharikar — Portfolio

Salesforce × AI developer portfolio. Single-file site (`index.html` + one photo), no build step needed.

## Deploy to GitHub Pages (5 minutes)

1. Create a new repo on GitHub named **`<your-username>.github.io`** (this makes the site live at that exact URL — cleanest for recruiters). Any other repo name works too, the URL just becomes `<your-username>.github.io/<repo-name>`.
2. Upload `index.html`, `README.md`, and the `assets/` folder (drag and drop works on github.com → "Add file" → "Upload files").
3. Go to the repo's **Settings → Pages** → under "Source" choose **Deploy from a branch** → branch `main`, folder `/ (root)` → Save.
4. Wait ~1 minute. Your site is live at `https://<your-username>.github.io/`.

Or from the command line:

```bash
cd portfolio
git init
git add .
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

## Customizing

- **Colors** — everything lives in the `:root` block at the top of `index.html` (`--wall`, `--red`, etc.).
- **Integration Wizard copy** — edit the `#wizard` section to match your project's real details.
- **Photo** — replace `assets/kalyani.jpg` with any photo; one taken against a plain blue wall blends best with the hero.
- **Crochet easter egg** — the floating 🧶 button at bottom-right. Add photos of your work inside the `.yarn-card` if you'd like.
