# LaTex-Publishing

## Description

If you want to publish your LaTex document on Github Pages as HTML and in releases as PDF, you can use this template repository, you just need to modify the [main.tex](./main.tex) file according to your needs.

Please put all the images in the [assets](./assets/) folder if you don't want to modify the [deploy-latex.yml](.github/workflows/deploy-latex.yml) file.

## Important Notes

- When you run the workflow for the first time, it will create a `gh-pages` branch, so please don't delete it, follow the [instructions](https://github.com/peaceiris/actions-gh-pages?tab=readme-ov-file#%EF%B8%8F-first-deployment-with-github_token) to create a Github Pages site.

- The compiled PDF file will be in the releases page always in the `Current` release as [main.pdf](https://github.com/MemerGamer/LaTex-Publishing/releases/download/Current/main.pdf). The PDF file will be overwritten in every release.
- The compiled HTML file will be in the [gh-pages](https://github.com/MemerGamer/LaTex-Publishing/tree/gh-pages) branch always with name, the HTML file will be overwritten in every release.
- The compilation time is around 8-10 minutes(because we use the full latex library), so please be patient.
