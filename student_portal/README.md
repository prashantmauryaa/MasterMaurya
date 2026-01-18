# Student Portal - Prashant University

A modern, responsive, and premium Student Portal Web UI built with HTML5 and CSS3.

## 🚀 Deployment Guide

This project is a **Static Website**, meaning it can be deployed to any static hosting provider without a backend server.

### Recommended Hosting Providers

#### 1. Netlify (Recommended)
1.  Drag and drop the `student_portal` folder into your Netlify dashboard.
2.  **Or** connect your GitHub repository and set the *Publish directory* to `student_portal` (or root if this is the only thing in the repo).

#### 2. Vercel
1.  Install Vercel CLI: `npm i -g vercel`
2.  Run `vercel` in this directory.
3.  **Or** push to GitHub and import the project into Vercel.

#### 3. GitHub Pages
1.  Push the code to a GitHub repository.
2.  Go to Settings > Pages.
3.  Select the branch (e.g., `main`) and folder (root) to deploy.

## 📂 Project Structure

```
/
├── index.html          # Landing Page
├── login.html          # Login Page
├── dashboard.html      # Main Student Dashboard
├── profile.html        # Student Profile Page
├── notices.html        # Notice Board Page
├── 404.html            # Error Page (Created for production)
├── robots.txt          # SEO Configuration
└── assets/
    └── css/
        └── style.css   # Main stylesheet (Design System)
```

## 🛠️ Customization

-   **Colors & Fonts**: Edit `assets/css/style.css` variables in the `:root` section.
-   **Images**: Currently using Unsplash placeholders. Replace `img` src attributes with your own assets.
-   **Icons**: Using Phosphor Icons (CDN included in head).

## 📄 License

&copy; 2024 Prashant University. All rights reserved.
