# Sanjay Bareth Portfolio & CV Website

This repository contains a professional multi-page personal portfolio website for **Sanjay Bareth**. It includes:

- Home page overview
- Detailed about page
- Full CV page
- Projects portfolio page
- Responsive, modern styling with semantic HTML and external CSS

## Pages Included

- `index.html` — Homepage with intro, short bio, and profile photo placeholder.
- `about.html` — Detailed profile, objective, highlights, and contact information.
- `cv.html` — Full CV with education, skills, internship, and experience.
- `projects.html` — Project portfolio with links and technology stacks.
- `style.css` — Shared professional styling.
- `assets/` — Static assets such as profile image placeholders.

## About Me

I am **Sanjay Bareth**, a Laravel Developer with prior Quality Analyst internship experience. I enjoy developing reliable, user-focused web applications and collaborating across teams to deliver high-quality digital products.

## How to Run Locally

Because this is a static site, you can run it with any local web server.

### Option 1: Python

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

### Option 2: VS Code Live Server

1. Open this repository in VS Code.
2. Install the **Live Server** extension (if not installed).
3. Right-click `index.html` and choose **Open with Live Server**.

## GitHub Pages Setup (`username.github.io`)

To host this site with GitHub Pages:

1. Create a repository named exactly: `username.github.io` (replace `username` with your GitHub username).
2. Push this code to the `main` branch of that repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` and `/ (root)`
5. Save and wait 1–2 minutes.
6. Your site will be live at:
   - `https://username.github.io`

## Customization Notes

- Replace `assets/profile-placeholder.svg` with your actual professional photo (e.g. `assets/profile.jpg`).
- Update social profile links in the footer (`LinkedIn`, `GitHub`) on all pages.
- Add more projects or testimonials as your portfolio grows.
