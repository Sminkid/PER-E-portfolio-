# PER-E-portfolio-

Professional e-portfolio website for Jonathan Chang, built with plain HTML, CSS, and JavaScript.

## Live Site

If GitHub Pages is enabled for this repository, the site is available at:

https://sminkid.github.io/PER-E-portfolio-/

## Project Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome icons (CDN)

## Project Structure

```
PER-E-portfolio-/
|- index.html
|- styles.css
|- script.js
|- README.md
|- assets/
	|- profile.jpg
	|- Jonathan_Chang_CV.pdf
	|- README.md
```

## Run Locally

### Option 1: VS Code Live Server

1. Open the project in VS Code.
2. Open index.html.
3. Right-click and select Open with Live Server.

### Option 2: Python HTTP server

Run this inside the project root:

```powershell
python -m http.server 5500
```

Then open:

http://localhost:5500

## Deploy with GitHub Pages

1. Push your latest code to the `main` branch.
2. Open repository Settings on GitHub.
3. Go to Pages.
4. Under Build and deployment:
	- Source: Deploy from a branch
	- Branch: main
	- Folder: / (root)
5. Click Save.
6. Wait 1 to 3 minutes for deployment.

## Notes

- The Download CV button points to `assets/Jonathan_Chang_CV.pdf`.
- The profile image is loaded from `assets/profile.jpg`.
- Keep file names and paths exactly the same unless you also update references in `index.html`.

## Author

Jonathan Chang