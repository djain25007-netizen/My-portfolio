# Daksh Jain — Portfolio Website

A responsive personal portfolio built with plain HTML, CSS and JavaScript.

## 1. Run locally
1. Extract `daksh-portfolio.zip`.
2. Open the `daksh-portfolio` folder in VS Code.
3. Install the **Live Server** extension (optional but recommended).
4. Right-click `index.html` → **Open with Live Server**.

You can also open `index.html` directly in a browser.

## 2. Add your profile photo
1. Choose a square JPG, PNG or WebP photo.
2. Copy it into the `assets` folder and name it `profile.jpg`.
3. In `index.html`, find:
   `src="assets/profile-placeholder.svg"`
4. Replace it with:
   `src="assets/profile.jpg"`

Use a clear, professional headshot. Keep the photo file inside `assets`.

## 3. Personalise your portfolio
- Update the About section in `index.html`.
- Update skill cards to show only skills you can confidently discuss.
- Replace the sample project cards, descriptions and GitHub links with your real projects.
- Update the GitHub profile URL in the navigation and social links.
- Add your resume PDF to the project folder (for example `assets/Daksh-Jain-Resume.pdf`) and add a button linking to it if you want a downloadable resume.
- Update email and LinkedIn links if they change.

## 4. Publish with GitHub Pages
1. Create a GitHub repository, for example `daksh-portfolio`.
2. Upload **all files and folders** from this project. Keep `index.html` in the repository root.
3. Open repository → **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. Your URL will look like:
   `https://YOUR-USERNAME.github.io/daksh-portfolio/`

## Notes
- This is a static website; no backend or database is required.
- The contact email link opens the visitor's default email application. It does not submit a message to a server.
- Google Fonts are loaded online. The site still works if they are unavailable, using fallback fonts.
