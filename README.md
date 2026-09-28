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

Project names, descriptions, URLs, and access labels are in `projects.js`.

- Facturoide and Nido are private and have no public links.
- [Better Sura](https://better-sura.vercel.app/) and [Cámara](https://camaras-cc6weex16-edymerchks-projects.vercel.app/) are public and link to the URLs provided by the owner.

For future projects, use a confirmed public HTTPS URL and `access: "Public"`, or `url: null` and `access: "Private"` for a private project. An unconfigured project with neither a URL nor a private label shows “Link coming soon”.

The supplied `../facturoide`, `../better-sura`, `../camaras-med`, and `../nido` paths were used to read project descriptions. They are local source directories, not deployed URLs. No private app data is included.

The GitHub profile link uses `edymerchk`, found in the Facturoide repository README. Confirm this is the profile you want to share.

## Publish on GitHub Pages

1. Review the project URLs and access labels in `projects.js`.
2. Push the files to a GitHub repository.
3. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then **main** and **/ (root)**, and save.

For a repository named `portafolio`, the default URL is `https://edymerchk.github.io/portafolio/`. A repository named `edymerchk.github.io` uses `https://edymerchk.github.io/` instead. Relative asset links work in both cases. `.nojekyll` keeps this a plain static site.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

The Editorial portfolio is implemented with the owner-provided project links and access labels; it has not been published.
