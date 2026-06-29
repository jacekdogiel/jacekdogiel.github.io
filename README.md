# Jacek Dogiel Portfolio

Static one-page portfolio for GitHub Pages.

## Run locally

```bash
python3 -m http.server 5173
```

Open `http://localhost:5173`.

## Build

No build step. Files are plain HTML/CSS and can be served directly.

## Deploy to GitHub Pages

1. Push repository to GitHub.
2. In GitHub, open **Settings -> Pages**.
3. Set source to the main branch and root folder.

For `jacekdogiel.github.io`, root deployment works as-is. For a project repository, root deployment also works because asset paths are relative. If this is later moved to Vite, set `base: "/"` for `jacekdogiel.github.io` or `base: "/<repo-name>/"` for a project repository.

## CV

Download file lives at `assets/Jacek_Dogiel_Senior_iOS_Engineer_CV.pdf`.
