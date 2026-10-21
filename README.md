# Vicky Kumar | Portfolio

Static portfolio site. No build step. Files: `index.html` and the `assets/` folder.

## Host on GitHub Pages
1. Create a new repo, for example `portfolio` (or `vickykumar03.github.io` for a root URL).
2. Upload `index.html` and the `assets` folder to the repo root.
3. Go to Settings > Pages > Source: "Deploy from a branch" > `main` / `/ (root)` > Save.
4. Open `https://vickykumar03.github.io/portfolio/` after a minute.

## Make the contact form send straight to your inbox
1. Go to https://web3forms.com, enter `vickykumar22032006@gmail.com` and copy the access key they email you.
2. In `index.html`, find `var FORM_KEY="";` and paste the key between the quotes.
Without a key, the form opens the visitor's email app instead.
