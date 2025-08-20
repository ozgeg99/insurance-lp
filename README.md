# Insurance Landing Page

This project contains an HTML landing page.

- `html-1` &ndash; the production-ready minified HTML.
- `index.html` &ndash; the formatted version for development.

## Development

Format the editable HTML with [Prettier](https://prettier.io/):

```sh
npx prettier index.html --write
```

## Production build

Generate the minified file used for deployment:

```sh
npx html-minifier-terser index.html -o html-1
```
