# Birding Manager

This repository hosts a simple static site that can be served with **GitHub Pages**.

## Deploying with GitHub Pages

1. Push this repo to GitHub.
2. In GitHub, open **Settings** → **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you want to publish (for example, `main`) and the **/ (root)** folder.
5. Save the settings. After a minute or two, your site should be available at:

```
https://shaanvaidya.github.io/birdingmanager/
```

## Using shaanvaidya.com/birdingmanager

GitHub Pages does **not** support custom domains on a subpath (like
`shaanvaidya.com/birdingmanager`) directly. To use that URL, keep GitHub Pages
as the host and add a **redirect or rewrite** on your existing
`shaanvaidya.com` hosting provider to send `/birdingmanager` to the GitHub Pages
URL above.

If you already set up a redirect for
`shaanvaidya.com/SanFranciscoStreetTreeMap`, you can add a similar rule for
`/birdingmanager`.
