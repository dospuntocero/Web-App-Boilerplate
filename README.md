# Web App Boilerplate

A front-end web application template based on [HTML5 Boilerplate](http://html5boilerplate.com)
and extended with [LESS](http://www.lesscss.org/) style sheets and [Gulp.js](http://gulpjs.com/)
task runner.


## Quick start

Clone the git repo:

```bash
git clone -o base https://github.com/KriaSoft/Web-App-Boilerplate.git MyApp
cd .\MyApp          # change the current directory to your project directory
npm install -g gulp # install gulp task runner globally, if you don't have it installed already
npm install         # install dev tools listed in the package.json file
```

Start a task runner to watch for modifications in source files and compile
modified files in the background:

```bash
gulp
```

And when you need to pull and merge the latest changes into your project, run:

```bash
git checkout master
git fetch base
git merge base/master
```


## Features

* HTML5 ready. Use the new elements with confidence.
* Cross-browser compatible (Chrome, Firefox, IE8+, Opera, Safari).
* Designed with progressive enhancement in mind.
* Includes [Normalize.css](http://necolas.github.com/normalize.css/) for CSS
  normalizations and common bug fixes.
* The latest [jQuery](http://jquery.com/) via CDN, with a local fallback.
* The latest [Modernizr](http://modernizr.com/) build for feature detection.
* Placeholder CSS Media Queries.
* Useful CSS helpers.
* Default print CSS, performance optimized.
* Protection against any stray `console.log` causing JavaScript errors in
  older browsers.
* An optimized Google Analytics snippet.
* Apache server caching, compression, and other configuration defaults for
  Grade-A performance.
* Cross-domain Ajax and Flash.
* "Delete-key friendly." Easy to strip out parts you don't need.
* Extensive inline and accompanying documentation.
* LESS-based style sheets


## Documentation

Take a look at the [documentation table of contents](doc/TOC.md). This
documentation is bundled with the project, which makes it readily available for
offline reading and provides a useful starting point for any documentation you
want to write about your project.


## Contributing

Anyone and everyone is welcome to [contribute](CONTRIBUTING.md).
