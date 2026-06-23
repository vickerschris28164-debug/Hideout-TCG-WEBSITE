# Hideout-TCG-WEBSITE

Static landing page for the HIDEOUT TCG community and weekly tournaments.

How to preview locally

1. Open `index.html` in your browser (double-click or use a local static server).
2. Or run:
```bash
cd /workspaces/Hideout-TCG-WEBSITE
python3 -m http.server 8000
```
Then open `http://localhost:8000`.

Leaderboard page

- View the leaderboard page at `leaderboard.html`.
- I can connect it to a live Google Sheet or ranked JSON list later.

Event rules

- The homepage now includes an event rules section for tournament behavior and match reporting.
- If you want, I can add more detailed rules for cash, webcam, and TCG Live play.

Info page

- View the information page at `info.html`.
- It includes event format descriptions, leaderboard explanation, FAQ, and payment details.

Add your photos and logo

- Put images (photos you want in the gallery) into `assets/images/`.
- Provide your logo file and I will integrate it into the header.

Next steps I can do for you

- Replace the gallery placeholder with your uploaded photos.
- Add a live leaderboard (Google Sheets or simple JSON).
- Add event scheduling and sign-up forms.

If you upload the photos and logo here, I'll integrate them and adjust the theme to match exactly.

## Backup and recovery

This repository stores the full website source, so if you run out of credits you can still access the site files and instructions here on GitHub.

## Custom domain setup

GitHub Pages can publish this site under a custom domain, but domain names cannot use underscores. Instead, use a name like `hideout-tcg.com` or `hideouttcg.com`.

Steps to connect a custom domain:
1. Register the domain with a registrar.
2. In your repository, create a file named `CNAME` containing the domain name.
3. In GitHub Settings > Pages, add the custom domain.
4. Update your DNS records with your registrar:
   - For an apex domain (`hideouttcg.com`), add A records to GitHub Pages IPs.
   - For a subdomain (`www.hideouttcg.com`), add a CNAME to `username.github.io`.

After DNS updates propagate, your site can load from the custom domain.

