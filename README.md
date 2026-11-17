# Sagar Bhond — DevOps Portfolio

A responsive static portfolio built with HTML, CSS and vanilla JavaScript. Designed for GitHub Pages.

## Project files

- `index.html` — portfolio content and page structure
- `style.css` — responsive visual styling
- `script.js` — mobile navigation and current year
- `assets/` — profile photo, Config Server LLP banner and résumé PDF

## Before publishing

1. Check the email, phone, LinkedIn and GitHub links in `index.html`.
2. Confirm that the résumé PDF in `assets/` is the version you want to publish publicly.
3. Confirm project descriptions and employer-approved public information.
4. If you want a custom domain, first set it in GitHub repository Settings → Pages. GitHub will create the `CNAME` file for branch-based publishing.

## Publish on GitHub Pages

1. Push the contents of this folder to the root of `https://github.com/SagarBhond/sagar-portfolio`.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for the deployment. The project URL should be `https://sagarbhond.github.io/sagar-portfolio/`.

## Custom domain

Keep the existing Hostinger nameservers if Hostinger is where the active DNS zone is managed. In GitHub repository **Settings → Pages**, enter your real domain under **Custom domain** and Save. Then configure the DNS records at Hostinger using the current GitHub Pages instructions:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

For an apex/root domain, GitHub currently documents these A records:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

For `www`, add a CNAME to `SagarBhond.github.io` (do not include the repository name). Do not delete email-related MX/TXT records. Remove only conflicting website records after checking what they do. Enable **Enforce HTTPS** after GitHub issues the certificate.

## Local preview

Open `index.html` in a browser. No build step or package installation is required.
