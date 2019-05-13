
# Jen Simmons dot com

## What is it?

The personal website of Jen Simmons. 
 
Built on top of Dan Urbanowicz’ [Eleventy Netlify Boilerplate](https://github.com/danurbanowicz/eleventy-netlify-boilerplate), for making a static website using the [Eleventy](https://www.11ty.io/) static site generator, with [Netlify CMS](https://www.netlifycms.org/) baked-in, deployed to [Netlify](https://www.netlify.com).


## Notes (for Jen) on Making This Thing Go

Navigate to `/admin`, and start editing content.


#### Locally, run Eleventy to build the site

```
npx eleventy
```

Or build automatically when a template changes:
```
npx eleventy --watch
```

Or in debug mode:
```
DEBUG=* npx eleventy
```
