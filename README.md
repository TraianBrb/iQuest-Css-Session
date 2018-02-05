# iQuest Cook Book

An awesome cook book!

## iQuest Requirements for development

The app should be responsive and must look good at least on safari mobile latest and chrome (desktop) latest.
The required minimum width should be 320px.
No library/framework is needed except fontawesome for the icons (http://fontawesome.io/get-started/) so please no bootstrap or similar, only html/css is allowed.

## Getting Started

The Build folder contains HTML, CSS and images files which were generated from Source folder using gulp.
The Source folder contains pug, sass and images.

*The HTML and CSS files are 100% readable, **but** I highly recommend reading the Source files: .pug and .scss*

### Prerequisites

You need to install node.js & npm

### Installing

From the root directory (where package.json is located), open the terminal and run

```
npm i
```

## Running

Run in terminal

```
gulp
```

It should open the iQuest Cook Book in your browser (http://localhost:3000)
Now you are using gulp and browsersync.

For more information check gulpfile.js file.

### Choices made throughout development

In styling the page, I used:

* Flexbox
```
display: flex;
```
with fallback on float
```
float: left;
```

* A sass mixin which calculates the font-size from px to em.

* None of my elements have fixed height, so nothing will break when they have larger content.

* At media screen (max-width: 320px) I chose to remove the text from header/footer buttons so they can have a cleaner look.

* Every clickable element received hover-state.

* Textarea elements are resizable only vertically.


## Built With

* [Pug](https://github.com/pugjs/pug) - Pug is a clean, whitespace sensitive syntax for writing html
* [Sass](https://github.com/sass/sass) - Sass is an extension of CSS, adding nested rules, variables, mixins, selector inheritance, and more.
* [Gulp](https://gulpjs.com/) - Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something.
* [Browser-sync](https://www.npmjs.com/package/browser-sync) - Keep multiple browsers & devices in sync when building websites.
* [Gulp-sass](https://www.npmjs.com/package/gulp-sass) - Used to compile SASS files into CSS
* [Gulp-pug](https://www.npmjs.com/package/gulp-pug) - Used to compile PUG templates into HTML
* [Gulp-autoprefixer](https://www.npmjs.com/package/autoprefixer) - Used to fix web browser differences
* [Gulp-group-css-media-queries](https://github.com/Se7enSky/group-css-media-queries) - Used to group media queries

## Authors

* **Traian Barbu** - [GitHub](https://github.com/TraianBrb)

## Acknowledgments

* iQuest University
