# Dr. Elaheh Salehi Rizi — Portfolio website

A multilingual (English, German, French), responsive static portfolio built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html` — page structure and content
- `styles.css` — visual design and responsive layout
- `script.js` — language switcher and small page enhancements

## Before publishing
1. In `index.html`, replace `https://www.linkedin.com/` with your actual LinkedIn profile URL.
2. Replace `YOUR.EMAIL@example.com` with the email address you want to publish.
3. Review every biography and project statement for accuracy.
4. Add a CV only if you want it publicly accessible. Do not upload confidential employer material, internal screenshots, source code or customer information.
5. Consider whether you want to publish the full doctoral-study detail as currently phrased.

## Publish with GitHub Pages (free)
1. Sign in to GitHub.
2. Create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io`.
3. Upload `index.html`, `styles.css`, `script.js` and this README to the repository root.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait for the deployment. Your site will be at `https://YOUR-GITHUB-USERNAME.github.io`.

GitHub Pages supports HTTPS. Enable **Enforce HTTPS** in Settings → Pages when the option appears.

## Privacy and security
- This is a static site: it has no database, login, forms, analytics or third-party scripts.
- The CSS currently imports Google Fonts. To avoid that external request, remove the `@import` line at the top of `styles.css`; system font fallbacks will be used.
- A public GitHub Pages repository makes the source code public. Only commit content you are comfortable publishing.
- Use two-factor authentication on your GitHub account.
- Do not publish home address, personal phone number, private documents or confidential employer information.

## Customization
Edit the text in `index.html` and the `translations` object in `script.js` together so all three language versions remain consistent.
