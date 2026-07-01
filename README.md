# Vonge

Vonge is a Personal portfolio/blog site template for Hugo. Browse through a [live demo](https://joyous-penguin.cloudvent.net/).
Increase the web presence of your brand with this configurable theme.


Vonge was made by [CloudCannon](http://cloudcannon.com/), the JAMStack Cloud CMS.
The component library is built and maintained for use with [Bookshop](https://github.com/cloudcannon/bookshop/)

Find more templates, themes and step-by-step Hugo tutorials at [CloudCannon Tutorials](http://cloudcannon.com/tutorials/).

[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/CloudCannon/vonge-hugo-bookshop-template)
## Features

* Component library for website building
* Fully configurable Website
* Pre-built pages
* Pre-styled components
* Blog
* Category pages
* Testimonials
* Portfolio
* Portfolio tags
* Live editing with [CloudCannon](http://cloudcannon.com/)
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Search engine optimisation

## Develop

### Requirements

This template is built with **Hugo Extended v0.143.1** (see `hugoVersion` in `.cloudcannon/initial-site-settings.json`). It requires the **extended** edition of Hugo (for Sass compilation) and a minimum version of **v0.128.0** (declared in `component-library/config.toml`).

Make sure you have installed:

* [Hugo Extended](https://gohugo.io/installation/) — v0.143.1 recommended (minimum v0.128.0)
* [Node.js](https://nodejs.org/) and npm (for Bookshop tooling)

Check your Hugo version and confirm it's the extended edition:
```bash
hugo version
```

### Running locally

Install the Node dependencies (Bookshop components are pulled in as Hugo modules, but the Bookshop tooling is installed via npm):
```bash
npm i
```

Then start the local development server:
```bash
hugo serve
```
The site will be available at `http://localhost:1313/`.

### Component browser

To generate the component browser:
```bash
npm run bookshop-browser
```
This will create browser files in the site's static directory. Running a Hugo build after this will show a live component browser at `/components`.

### Troubleshooting

If there is a bookshop error when running locally, try updating bookshop:
```bash
npx @bookshop/up@latest
```

## Structure
The bookshop components live in `component-library`, which is loaded as a Hugo module in `site/config.toml`.

The site also pulls in the main dependency of `github.com/cloudcannon/bookshop/hugo/v3`.

For further help with Bookshop, see the [Bookshop Guides](https://github.com/CloudCannon/bookshop).
