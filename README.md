# Benjamin Obeng — Developer Portfolio

Personal software development and freelance services website built with React and Vite.

## Local development

```bash
npm install
npm run dev
```

## GitHub Pages

A GitHub Actions workflow in `.github/workflows/deploy.yml` builds the Vite app with the correct `/portfolio-/` base path and deploys the `dist` directory.

1. Open **Settings → Pages** in the GitHub repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Open **Actions** and run the **Deploy portfolio to GitHub Pages** workflow if needed.
4. Once successful, the expected address is https://obeng-21.github.io/portfolio-/ .

**Important:** GitHub Pages for private repositories requires an eligible paid GitHub plan. If your plan does not support it, make the repository public in **Settings → General → Danger Zone → Change repository visibility**. Do not publish secrets or private client data.

## Contact form

The project enquiry form opens a prefilled email in the visitor's email application. It does not yet send or store submissions on a server. Visitors must send the email themselves.

## Portfolio

Project entries are illustrative descriptions. Add verified demos and screenshots before sharing publicly.
