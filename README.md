# Plotpoint Landing Page & Support Site

The official, public-facing website repository for the **Plotpoint** iOS & macOS mobile application, owned by **Caldwell Apps**. 

This repository serves as the public landing page, customer support portal, and holds the legally required **Privacy Policy** and **Terms of Service** documentation required for submission and approval on the Apple App Store.

## Features

- **Responsive Landing Page**: Sleek, modern charcoal-green theme designed to align with the native app's aesthetics.
- **Interactive Documentation**: Single-page hash routing (`#privacy`, `#terms`) to allow direct links for App Store Connect reviewers.
- **Support Forms**: Contact routes mapping to `support@caldwellapps.com` to handle support tickets.
- **100% Client-Side**: Powered by vanilla HTML, CSS, and JS. Loads instantly and runs entirely on the browser with zero external dependencies.

## Live Website

The website is hosted on GitHub Pages:
- **Landing Page & Support**: [https://CaldwellApps.github.io/plotpoint-app/](https://CaldwellApps.github.io/plotpoint-app/)
- **Privacy Policy**: [https://CaldwellApps.github.io/plotpoint-app/#privacy](https://CaldwellApps.github.io/plotpoint-app/#privacy)
- **Terms of Service**: [https://CaldwellApps.github.io/plotpoint-app/#terms](https://CaldwellApps.github.io/plotpoint-app/#terms)

## Local Development

To run or preview the website locally on your computer:

1. Clone this repository:
   ```bash
   git clone https://github.com/CaldwellApps/plotpoint-app.git
   ```
2. Open the directory:
   ```bash
   cd plotpoint-app
   ```
3. Open `index.html` in any web browser to view:
   ```bash
   open index.html
   ```

## Deployment on GitHub Pages

This project is configured to deploy automatically via GitHub Pages from the root of the `main` branch. 

To redeploy changes:
1. Commit updates to your local repository.
2. Push your commits to GitHub:
   ```bash
   git push origin main
   ```
3. GitHub Actions will rebuild and deploy the site live within 1–2 minutes.
