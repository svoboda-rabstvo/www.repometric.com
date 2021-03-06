# INFO

## Develop
### Assets
> Commonly used [assests](https://github.com/repometric/assets) added as a [git submodule](https://github.com/blog/2104-working-with-submodules).
### Styles
> [Bootstrap 3](https://getbootstrap.com/) for layouts and responsive design + custom [CSS3 media queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp).
### Fonts
> Free fonts from [Google Fonts](https://fonts.google.com/) and icons from [Font Awesome](http://fontawesome.io/).
### Favicons
> Autogenerated from SVG logo using [RealFaviconGenerator](https://realfavicongenerator.net/faq), the result adapted for all major [browsers](https://realfavicongenerator.net/favicon_compatibility). [IE browserconfig](https://msdn.microsoft.com/en-us/library/dn320426) generated as well.
### Scripts
> [jQuery](https://jquery.com/) for DOM manipulation and AJAX requests, [The HTML5 Shiv](https://github.com/aFarkas/html5shiv) and [RespondJS](https://github.com/scottjehl/Respond) for better CSS3 and HTML5 support in old IE.

## Build
### Gulp
> [Gulp](http://gulpjs.com/) for all optimisations and automations as specified in `gulpfile.js`, basically to copy all required files to `www` folder. More details about plugins below.
### Sitemap
> [Sitemap](https://www.sitemaps.org) generated with [gulp-sitemap](https://www.npmjs.com/package/gulp-sitemap).
### Robots
> [Robots file](http://www.robotstxt.org/) created with [gulp-robots](https://www.npmjs.com/package/gulp-robots).
### Inline
> Scripts and Styles (except external) inlined using [gulp-inline-source](https://www.npmjs.com/package/gulp-inline-source).
### Inject
> Parts of the page that are optional for development injected using [gulp-inject](https://www.npmjs.com/package/gulp-inject) (Social Metainfo & Analytics).
### Minification
> HTML, CSS & JS minified by [html-minifier](http://kangax.github.io/html-minifier/), [clean-css](https://jakubpawlowicz.github.io/clean-css/), [UglifyJS](http://lisperator.net/uglifyjs/)
### Travis
> [Build, test and deploy](https://travis-ci.org/repometric/landing) all together using `.travis.yml` config. Every merge to `master` triggers build and deploy to `gh-pages` branch.

## Run
### Domain
> `repometric.com` regirested via [GoDady](https://godaddy.com).
### GitHub Pages
> Serve landing from `gh-pages` branch using [GitHib pages](https://pages.github.com/) and [custom domain](https://help.github.com/articles/using-a-custom-domain-with-github-pages/) from `CNAME` config.
### Jekyll
> [Completely bypass Jekyll processing](https://github.com/blog/572-bypassing-jekyll-on-github-pages) for GitHub pages with `.nojekyll` file.
### Cloudflare
> `https` not available for custom domains at GitHub Pages, [moving DNS to Cloudflare](https://hackernoon.com/set-up-ssl-on-github-pages-with-custom-domains-for-free-a576bdf51bc) solved it
; in addition it allows to minify and compress traffic, cache it, provides CDN and many many more.

## Extra
### Emails
> [Mailchimp](https://mailchimp.com/) integrated for managing email campaigns.
### Google Analytics
> Analyze website and traffic using [Google Analytics](https://www.google.com/analytics).
### Yandex Metrica
> The same with [Yandex Metrica](https://metrica.yandex.com).
### Open Graph
> Page described as `website` using [Open Graph](http://ogp.me/), so it has customized preview and description.
### Twitter Cards
> The same for [Twitter Cards](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/overview/markup).
### Structured Data
> [Page described](http://schema.org/) as `organisation` in form of [JSON-LD](https://developers.google.com/search/docs/guides/intro-structured-data#structured-data-format).
