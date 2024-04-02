# Vonge

Vonge is a Personal portfolio/blog site template for Hugo. Browse through a [live demo](https://jazzed-kale.cloudvent.net/).
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

To run locally:
```bash
hugo serve
```

To generate the component browser:
```bash
npm run bookshop-browser
```
This will create browser files in the site's static directory. Running a Hugo build after this will show a live component browser at `/components` 

If there is a bookshop error when running locally, try updating bookshop:
```bash
npx @bookshop/up@latest
```

## Structure
The bookshop components live in `component-library`, which is loaded as a Hugo module in `site/config.toml`.

The site also pulls in the main dependency of `github.com/cloudcannon/bookshop/hugo/v3`.

For further help with Bookshop, see the [Bookshop Guides](https://github.com/CloudCannon/bookshop).
