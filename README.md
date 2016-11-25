# [citrusui blog](https://blog.citrusui.me)

# Status

[![Build Status](https://travis-ci.org/citrusui/blog.svg?branch=master)](https://travis-ci.org/citrusui/blog)
[![devDependencies Status](https://david-dm.org/citrusui/blog/dev-status.svg)](https://david-dm.org/citrusui/blog?type=dev)

My very awesome [Jeykll](https://jekyllrb.com) blog.

There's a lot of tweaks and modifications to the Sass files, but for the most part, this site uses [Poole](http://getpoole.com).

# Scripts

`npm run dev`: Runs Jekyll as `development` and watches for any changes.

`npm run lint`: Lints all Sass files in `_sass` according to rules in `.sass-lint.yml`.

`npm run prepare`: Deploys to Firebase as production before publishing to npm. Requires npm@4.

`npm run prod`: Runs Jekyll with the `production` environment. This overrides `localhost` in favor of `site.url`.

## Terms

Licensed under [MIT](LICENSE.md). If you use any part of this code, please link back to this repository, thanks!
