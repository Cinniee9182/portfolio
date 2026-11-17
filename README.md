# Cinnie | SEO & Growth Portfolio

Static portfolio site (HTML + CSS, no build step, no dependencies).

## Structure

```
index.html          the whole site
assets/portrait.jpg portrait photo
.nojekyll           tells GitHub Pages to serve files as they are
```

## Run locally

Open `index.html` in a browser.

## Deploy on GitHub Pages

1. Push this folder to a new GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

For a shorter address (`https://<your-username>.github.io/`), name the repository `<your-username>.github.io`.

## Edit

- Text and numbers: edit `index.html` directly.
- Colors: change the variables at the top of the `<style>` block (`--bg`, `--ink`, `--accent`).
- Portrait: replace `assets/portrait.jpg` and keep the same file name.
