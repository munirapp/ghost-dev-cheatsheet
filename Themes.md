# Cheatsheet Themes

Ghost has `theme layers` to give developers and designers the flexibility to build custom publications that are powered by the Ghost platform. By default, all files about styles and structure themes located on `./content/themes/`, see the official ghost's documentation for more reference [https://ghost.org/docs/themes/](https://ghost.org/docs/themes/).

## Stack Library

For theme styles, tools, and templates, Ghost uses the following stack libraries:

### HandleBars

[Handlebars](https://handlebarsjs.com/) is a simple templating language. It uses a template and an input object to generate HTML or other text formats. Handlebars templates look like regular text with embedded Handlebars expressions. `Handlebars` adopt a `Logic-Less template` that follows the philosophy that there should be little to no logic in your templates. Ghost use [Express](https://expressjs.com/) library in their core. So to integrate with handlebars, Ghost create a custom library called [express-hbs](https://www.npmjs.com/package/express-hbs). Indirectly, for now we **can't** use any other `Logic-Less template` besides `Handlebars` such as `mustache.js`, `dust.js`, etc.
