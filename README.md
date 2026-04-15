# aocyber-oss

Source for the AO Cyber Systems open source landing site, built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages.

## Local development

```sh
hugo server
```

## Deployment

Pushes to `main` trigger `.github/workflows/hugo.yml`, which builds the site and publishes it to GitHub Pages.

In the repo settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.

## Adding a project

Edit the `[[params.projects]]` entries in `hugo.toml`.
