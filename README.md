# Heroku Buildpack for CasperJS

This is a [Heroku buildpack] for apps that require [CasperJS] and [PhantomJS]
binaries.

To use multiple buildpacks, use [heroku-buildpack-multi].

Note: If you're developing a Node.js app, instead of installing this buildpack,
you can simply list `phantomjs` and `casperjs` in your `package.json`. Heroku's
standard Node.js buildpack automatically adds `node_modules/.bin` to `$PATH`.

[Heroku buildpack]: https://devcenter.heroku.com/articles/buildpacks
[CasperJS]: http://casperjs.org/
[PhantomJS]: http://phantomjs.org/
[heroku-buildpack-multi]: https://github.com/heroku/heroku-buildpack-multi
