# Personal Blog

A minimal static blog with a clean, readable design.

## Structure

```
website/
├── index.html          # Homepage with post list
├── style.css           # All styles
├── blog/               # Blog posts
│   ├── welcome.html
│   └── thoughts-on-writing.html
└── .nojekyll           # For GitHub Pages
```

## Adding New Posts

1. Create a new HTML file in the `blog/` folder
2. Copy the structure from an existing post
3. Update the title, date, and content
4. Add a link to it in `index.html`

## Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Push your code:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

3. Go to repository Settings → Pages
4. Set source to "Deploy from a branch"
5. Select `main` branch and `/ (root)` folder
6. Save

Your blog will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Preview Locally

Open `index.html` in your browser, or use a simple server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Customization

Edit `style.css` to change colors, fonts, or layout. The current design uses:
- Earth tone colors (warm creams, browns, taupes)
- Georgia serif for body text
- Minimal, clean layout with lots of whitespace
