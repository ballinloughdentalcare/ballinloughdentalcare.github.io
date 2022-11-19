# Ballinlough Dental Care

A dentist's [website](https://ballinloughdentalcare.ie/).

## Development

To build locally, you'll need [node.js][] or an equivalent. Then run `npm
install` to get the software, and `npm run build` to build the HTML, JavaScript
and CSS which make up the site.

## TODO

The site was previously hosted on Heroku, and the sources in
github.com/ballinloughdentalcare/ballinloughdentalcare.. Since GitHub
introduced their Actions feature, however, we've decided to keep everything
there, including the hosting. While on Heroku, the site was rendered with an
express.js server (which converted the pug/stylus/coffee sources to
html/css/js), here it must be static. Therefore the Cakefile needs to be
rewritten. The source files are moved to `src/`. Finally, this repo was created
with the name ballinloughdentalcare.github.io, to ensure it is hosted at
https://ballinloughdentalcare.github.io, which will serve as the value of the
DNS CNAME at ballinloughdentalcare.ie.

- [ ] Static generation
- [ ] Host on GitHub
- [ ] GitHub Actions
- [ ] DNS

[node.js]: https://nodejs.org/en/
