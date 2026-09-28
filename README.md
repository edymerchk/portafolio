# Edy Laverde — portfolio

A responsive personal portfolio using the Editorial design: a quiet introduction and an easy-to-scan list of four projects.

## Stack

Plain HTML, CSS, and a small JavaScript file. No framework, packages, or build step. Google Fonts supplies DM Sans and Manrope, with system fallbacks if unavailable. All other assets are local.

## Preview

Open `index.html` in a browser, or run this in the project directory:

```sh
python3 -m http.server 8080
```

Visit http://localhost:8080 to view the portfolio.

## Project links

Project names and descriptions are in `projects.js`. Replace each `url: null` with its confirmed public HTTPS URL. Use `access: "Private"` for a private project; it can remain without a link. Use `access: "Public"` if you want an explicit public label. Until configured, a project shows “Link coming soon” rather than a broken link.

The supplied `../facturoide`, `../better-sura`, `../camaras-med`, and `../nido` paths were used to read project descriptions. They are local source directories, not deployed URLs. No private app data is included.

The GitHub profile link uses `edymerchk`, found in the Facturoide repository README. Confirm this is the profile you want to share.

## Publish on GitHub Pages

1. Configure the public project URLs and access labels in `projects.js`.
2. Push the files to a GitHub repository.
3. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then **main** and **/ (root)**, and save.

For a repository named `portafolio`, the default URL is `https://edymerchk.github.io/portafolio/`. A repository named `edymerchk.github.io` uses `https://edymerchk.github.io/` instead. Relative asset links work in both cases. `.nojekyll` keeps this a plain static site.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

The Editorial portfolio is implemented; it has not been published. Its external project links still need confirmation.
