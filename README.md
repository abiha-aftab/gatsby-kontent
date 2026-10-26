# gatsby-kontent

A blog built while learning Gatsby with Kentico Kontent as the headless CMS (September 2021).
It started from Kentico's [gatsby-starter-kontent-lumen](https://github.com/Kentico/gatsby-starter-kontent-lumen)
and adds a small local plugin (`plugins/kontent-used-by-content-items`) that shows which content items reference each other.

**Stack:** Gatsby, React, SCSS, Kentico Kontent (`@kentico/gatsby-source-kontent`).

## Run locally

```bash
npm install
cp .env.template .env   # add your Kontent project ID
npm run develop
```
