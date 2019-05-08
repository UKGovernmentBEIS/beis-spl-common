# BEIS SPL common

*Forked from [GDS Node.js boilerplate](https://github.com/alphagov/gds-nodejs-boilerplate).*

This is a skeleton Node.js app running on [Express] with [Nunjucks] as a template engine.

It includes:
- Grunt for compliation of sass/js
- [GOV.UK Frontend]
- [Browserify] with babelify and Nunjucksify
- Mocha for testing
- Middleware to set correlation headers
- i18n language support
- [Snyk]
- [StandardJS] for linting

To get started clone the repo and run

``` bash
$ npm install
$ npm start
```
(`npm install` might error about Snyk if it’s not set up but ignore for now)

Then go to [http://localhost:3000/](http://localhost:3000/) to see it in action.

[Express]: https://expressjs.com/
[Nunjucks]: https://mozilla.github.io/nunjucks/
[Snyk]: https://snyk.io/
[GOV.UK Frontend]: https://design-system.service.gov.uk/
[Browserify]: http://browserify.org/
[StandardJS]: https://standardjs.com/
