# Heroku Buildpack for CasperJS

This is a [Heroku buildpack] for apps that require [CasperJS] and [PhantomJS]
binaries.

Note: If you're developing a Node.js app, instead of installing this buildpack
(typically through [heroku-buildpack-multi]), you can simply list `phantomjs`
and `casperjs` in your `package.json`. Heroku's standard Node.js buildpack
automatically adds `node_modules/.bin` to `$PATH`.

[Heroku buildpack]: http://devcenter.heroku.com/articles/buildpacks
[CasperJS]: http://casperjs.org/
[PhantomJS]: http://phantomjs.org/
[heroku-buildpack-multi]: https://github.com/ddollar/heroku-buildpack-multi
