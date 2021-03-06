# Development & Deployment
- Make changes on master (or branch of your choice).
- Make sure to `npm build` or `npm start` to verify changes and cause `dist` folder to be updated.
- run `./deploy.sh`
  - this pushes the `dist` subfolder as a branch to `gh-pages`
- Github pages settings are configured to publish the `gh-pages` root folder 
- Github pages settings are configured to redirect to mitchellbarnesphoto.com.
- GoDaddy is configured with `A` records to point go Github pages.

## Downloading fonts
- Find font source online, download .zip file (e.g. dafont.com)
- Upload to font generator (e.g. www.web-font-generator.com)
- Downloaded generated .zip file
- Copy 2 `@font_face` definitions into .scss file (e.g. _typography.scss)
- Copy `.eot`, `.ttf`, and `.svg` files into appropriate scss folder
- Use font name in scss!
- For an example, check out `BradleyHandITC` or `LucidaHandwriting-Italic`
 
# [Start Bootstrap - Grayscale](https://startbootstrap.com/themes/grayscale/)

[Grayscale](http://startbootstrap.com/themes/grayscale/) is a multipurpose, one page HTML theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/).

## Preview

[![Grayscale Preview](https://startbootstrap.com/assets/img/screenshots/themes/grayscale.png)](https://blackrockdigital.github.io/startbootstrap-grayscale/)

**[View Live Preview](https://blackrockdigital.github.io/startbootstrap-grayscale/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-grayscale/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-grayscale.svg)](https://www.npmjs.com/package/startbootstrap-grayscale)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-grayscale.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-grayscale)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:

- [Download the latest release on Start Bootstrap](https://startbootstrap.com/themes/grayscale/)
- Install using npm: `npm i startbootstrap-grayscale`
- Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-grayscale.git`
- [Fork, Clone, or Download on GitHub](https://github.com/BlackrockDigital/startbootstrap-grayscale)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with `dist` directory. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

Clone the source files of the theme and navigate into the theme's root directory. Run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `package.json` file to see which scripts are included.

#### npm Scripts

- `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
- `npm run build:assets` copies the files in the `src/assets/` directory into `dist`
- `npm run build:pug` compiles the Pug located in the `src/pug/` directory into `dist`
- `npm run build:scripts` brings the `src/js/scripts.js` file into `dist`
- `npm run build:scss` compiles the SCSS files located in the `src/scss/` directory into `dist`
- `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
- `npm run start:debug` runs the project in debug mode
- `npm start` or `npm run start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`

You must have npm installed in order to use this build environment.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/BlackrockDigital/startbootstrap-grayscale/issues) here on GitHub or leave a comment on the [theme overview page at Start Bootstrap](http://startbootstrap.com/themes/grayscale/).

## About

Start Bootstrap is an open source library of free Bootstrap themes and templates. All of the free themes and templates on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

- <https://startbootstrap.com>
- <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

- <http://davidmiller.io>
- <https://twitter.com/davidmillerskt>
- <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2020 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-grayscale/blob/gh-pages/LICENSE) license.
