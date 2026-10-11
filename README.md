# Field's Support Hub

A responsive, dark-charcoal and neon-green static creator support page designed for GitHub Pages.

## Files

- `index.html` — page structure and placeholder PromptPay QR panel
- `style.css` — visual design and responsive layout
- `script.js` — tiny progressive enhancement for the copyright year

## Important payment note

This starter contains **no real payment credentials and no real QR code**. The QR-like illustration is a clearly labelled placeholder. The payment button is disabled.

Before accepting public contributions:
1. Ask KBank whether your account and age are eligible for this use, and whether guardian consent is required.
2. Obtain a receiving QR from K PLUS or another official KBank channel.
3. Replace the placeholder panel with the bank-generated QR image only after eligibility is confirmed.
4. Keep your national ID, home address, bank login, PIN, password, and OTP out of this website and repository.
5. Never represent a transfer as completed based only on a screenshot; verify it in your bank app.

## Deploy to GitHub Pages

1. Create a new GitHub repository, for example `fields-support-hub`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The URL will typically look like `https://YOUR-USERNAME.github.io/fields-support-hub/`.

If you want a custom domain later, configure it in GitHub Pages settings.

## Add a link from Logic Calculator

Once deployed, link the calculator's support button to your published support page, for example:

```html
<a href="https://YOUR-USERNAME.github.io/fields-support-hub/" target="_blank" rel="noopener noreferrer">
  ☕ Support this project
</a>
```

Replace `YOUR-USERNAME` with your GitHub username.
