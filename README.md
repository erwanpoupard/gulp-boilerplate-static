# Gulp static boilerplate

A boilerplate you can make your sites with.

## specifics

* html written in pug (jade)
* css
    * written in scss
    * minified
    * autoprefixed
* js
    * browserified (you can use `require('something')`)
    * minified
    * checked with jshint
    * babel for ES6
* images
    * optimised (slight loss in quality)
    * lossless optimisations
* gulp for building
* editorconfig
* BrowserSync ([localhost:3000](http://localhost:3000))

## folder structure

```
*.pug
includes/
  *.pug
src/
    js/
        *.js
    scss/
        *.scss
    img/
        *.svg
        *.png
        *.jpg
assets
    *.*
dist
    #output
gulpfile.js
package.json
.jshintrc
.editorconfig
.gitignore
```

## usage

First install all node packages with `npm install`, then you can build the site with `gulp`, and if you want to keep watching for changes after that `gulp watch` (both at the same time is done with `gulp default watch`).

## license

MIT
