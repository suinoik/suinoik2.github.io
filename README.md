# Professional Portfolio GitHub Pages Site

A static portfolio site for Onwuosiuno Ikhioda.

## Publish from the `suinoik2.github.io` project repository

Because the repository belongs to the `suinoik` GitHub account, GitHub Pages publishes it as a project site at:

`https://suinoik.github.io/suinoik2.github.io/`

### Terminal commands

```bash
cd suinoik2.github.io
git init
git add .
git commit -m "Update professional portfolio"
git branch -M main
git remote add origin https://github.com/suinoik/suinoik2.github.io.git
git push -u origin main
```

If the remote already exists:

```bash
git remote set-url origin https://github.com/suinoik/suinoik2.github.io.git
git add .
git commit -m "Update Artifact 1 portfolio content"
git push
```

Then open the repository on GitHub and go to:

**Settings → Pages → Build and deployment → Deploy from a branch → main / root → Save**

## Local preview

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
