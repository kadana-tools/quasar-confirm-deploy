publicPath:

  publicPath: process.env.NODE_ENV === "production" ? "/quasar-standardapp-deploy/" : "/",

during git push:

  git subtree push --prefix dist/spa origin gh-pages

