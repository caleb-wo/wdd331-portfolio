# WDD 331R Portfolio

**Student:** Caleb M. Wolfe
**Semester:** Fall 2026; Senior
**Live Site:** [View Site 💻](https://caleb-wo.github.io/wdd331-portfolio/)

## About

This repository is my portfolio for WDD 331R: Advanced CSS. Each week I add new pages and styles as I work through the course assignments. The site deploys automatically to GitHub Pages on every push to main via an Actions workflow provided for the class.

The CSS is built using [LightningCSS](https://lightningcss.dev/) with [pnpm](https://pnpm.io/). I also use [Parcel](https://parceljs.org/) for live reload. Ordinarily, I wouldn't use LightningCSS directly, I'd just use Parcel. However, through this course I studied CSS build tools specifically, which is why I don't package the project with Parcel, currently.

To build the css, simple run `pnpm build`. This fires off a script in [package.json](./package.json).

## Pages

- [Home](./index.html)
- [Unit-1: Custom Properties](./units/unit-1/custom-properties/index.html)
- [Unit-2: Layered Components](./units/unit-2/layered-components/index.html)
