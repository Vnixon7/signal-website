# Signal website

A static website for Signal — Article Trust Score.

## Files

- `index.html` — landing page
- `why-signal.html` — founder/motivation post
- `privacy.html` — privacy policy page
- `styles.css` — all styling
- `assets/signal-icon-128.png` — icon

## How to preview locally

Open `index.html` in your browser.

Or run a simple local server:

```bash
cd signal-website
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## How to publish fast with GitHub Pages

1. Create a new GitHub repository, for example `signal-website`.
2. Upload all files from this folder.
3. Go to repository **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. GitHub gives you a public URL like:
   `https://YOUR_USERNAME.github.io/signal-website/`

Use that URL for your Chrome Web Store website/support URL.

For the privacy policy URL, use:

```text
https://YOUR_USERNAME.github.io/signal-website/privacy.html
```

## How to publish with Netlify

1. Go to Netlify.
2. Drag and drop the `signal-website` folder into the deploy area.
3. Netlify gives you a public URL.
4. Use `/privacy.html` as the privacy policy URL.

## Before launch

Update the install button in `index.html` once your Chrome Web Store link is available:

```html
<a class="button primary" href="YOUR_CHROME_WEB_STORE_URL">Install on Chrome</a>
```
