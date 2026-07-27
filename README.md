# Professional Portfolio GitHub Pages Site

A static portfolio site for Onwuosiuno Ikhioda.

## Publish at https://suinoik2.github.io

This URL requires a GitHub repository named exactly:

`suinoik2.github.io`

### Terminal commands

```bash
cd suinoik2.github.io
git init
git add .
git commit -m "Launch professional portfolio"
git branch -M main
git remote add origin https://github.com/suinoik/suinoik2.github.io.git
git push -u origin main
```

Then open the repository on GitHub and go to:

**Settings → Pages → Build and deployment → Deploy from a branch → main / root → Save**

GitHub Pages should publish the site within a few minutes.

## Local preview

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
