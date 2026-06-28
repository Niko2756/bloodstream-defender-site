# Bloodstream Defender Site

Static GitHub Pages starter site for Bloodstream Defender.

## Before Publishing

Replace `REPLACE_WITH_SUPPORT_EMAIL_BEFORE_PUBLISHING` in:

- `support/index.html`
- `privacy/index.html`

Use a real public support email, because App Store Connect needs a support page with working contact information.

## Local Preview

From this folder:

```sh
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173/
```

## GitHub Pages Setup

Recommended repo name:

```text
bloodstream-defender-site
```

After the email placeholder is replaced:

```sh
git init
git add .
git commit -m "Create Bloodstream Defender support site"
gh repo create bloodstream-defender-site --public --source=. --remote=origin --push
```

Then enable Pages in GitHub:

```text
Settings > Pages > Source: Deploy from a branch > Branch: main > Folder: /root > Save
```

Expected URLs after publishing:

```text
https://Niko2756.github.io/bloodstream-defender-site/
https://Niko2756.github.io/bloodstream-defender-site/support/
https://Niko2756.github.io/bloodstream-defender-site/privacy/
```
