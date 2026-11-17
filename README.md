# Sagar Bhond — DevOps Portfolio

Static portfolio website built with HTML, CSS and vanilla JavaScript.

## Publish / repair GitHub Pages

This package includes a GitHub Actions workflow at
`.github/workflows/deploy-pages.yml`. It publishes the repository root to GitHub Pages
whenever you push to the `main` branch.

1. Extract this ZIP.
2. Open your repository: https://github.com/SagarBhond/sagar-portfolio
3. Upload **the contents** of the extracted folder to the repository root (not the ZIP
   itself and not an extra enclosing folder). Keep the `.github` folder.
4. Commit the changes to the `main` branch.
5. In GitHub, open **Settings → Pages**.
6. Under **Build and deployment → Source**, select **GitHub Actions**.
7. Open the **Actions** tab and wait for **Deploy portfolio to GitHub Pages** to finish
   successfully.
8. Visit https://sagarbhond.github.io/sagar-portfolio/

## If the site still shows 404

- Confirm the repository is named exactly `sagar-portfolio` and is public, or that your
  GitHub plan/settings allow Pages for a private repository.
- Confirm the workflow ran on the `main` branch and completed successfully.
- In **Settings → Pages**, confirm the deployment source is **GitHub Actions**.
- Wait a few minutes after the first successful deployment, then hard-refresh the page.
- If a custom domain is configured but you do not use it, remove the custom-domain entry
  under **Settings → Pages**. Do not delete DNS/email records without checking them.

## Local preview

Open `index.html` in a browser. No build tools or package installation are required.

## Included assets

- `assets/sagar-bhond-profile.png`
- `assets/config-server-devops-banner.png`
- `assets/Sagar-Bhond-Resume.pdf`

Review the résumé and contact details before publishing them publicly.
