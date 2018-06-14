# Quasar App

> Includes bikes.vue test

> To launch a site in development mode (hot-code reloading, error reporting, etc) on port 8083:

> quasar dev -p 8083

> View details: http://localhost:8083/bikes

> View on GitHub: https://smartparks.github.io/quasar1

> Issue: "bikes" route returning 404 on GitHub

> (After testing, delete files and folders copied from docs folder to root)

> To generate a static site:
> quasar build

> To deploy dist on GitHub https://gist.github.com/cobyism/4730490

> Remove /dist from .gitignore

> git add dist/spa-mat && git commit -m "Initial dist/spa-mat subtree commit"

> FOR DEPLOYING STATIC SITE (deploy with GitHub desktop first)
> git subtree push --prefix dist/spa-mat origin gh-pages


> bikemap.html page is not vueJS: https://smartparks.github.io/quasar1/bikemap.html

> Didn't use, used gh-pages instead.
> quasar.conf.js > build
> distDir: 'docs',

> Added to quasar.conf.js > build
> assetsPublicPath: './',
> https://github.com/jeneser/vue-cli-ghpages

> Install once globabally:
> npm install -g vue-cli-ghpages

> Run everytime for static routing
> vue-cli-ghpages --dir dist/spa-mat

> Then copy from dist/spa-mat to root


> NOT DOING
> In dist/spa-mat/index.html, replace:

> src=/js with src=/quasar1/js

> href=/app with href=/quasar1/app
