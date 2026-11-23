# RED X HACKER — Website

A responsive, single-page gaming community landing page using plain HTML, CSS and JavaScript.

## Before publishing
Open `index.html` and find `SITE_CONFIG` near the bottom. Replace:
- `https://t.me/YOUR_TELEGRAM_CHANNEL` with your real Telegram channel link.
- `https://wa.me/91XXXXXXXXXX` with your WhatsApp link. Use country code and digits only, e.g. `https://wa.me/91...`.

Do not publish until both links are updated. The current placeholders are not working contact links.

## Android + Vercel deployment (GitHub method)
1. Download and extract this ZIP on your Android phone.
2. Open GitHub in Chrome and sign in (or create an account).
3. Tap **New repository**. Name it `red-x-hacker-website`; choose **Public** or **Private**, then create it.
4. Open the repository → **Add file** → **Upload files**.
5. Upload `index.html` (and optionally `README.md`) from the extracted folder. Make sure `index.html` is in the repository root, not inside another folder.
6. Tap **Commit changes**.
7. Open Vercel in Chrome and sign in using GitHub.
8. Tap **Add New → Project**, import `red-x-hacker-website`.
9. Framework Preset: **Other**. Build Command and Output Directory can be left blank for this plain HTML site. Click **Deploy**.
10. After deployment, open the Vercel URL to test the page and both buttons.

## Updating the website
Edit `index.html` in a text/code editor, save it, then upload the changed file to the same GitHub repository and commit. Vercel automatically redeploys.

## Files
- `index.html` — complete website, styles, animations and button links.
- `vercel.json` — basic Vercel configuration.
