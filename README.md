<div align="right">
  <img src="https://img.shields.io/badge/Completion-100%25-blue.svg" />
  <a href="https://github.com/Hsins/udemy_travel-site/blob/master/LICENSE" alt="License">
    <img src="https://img.shields.io/github/license/Hsins/udemy_travel-site.svg" />
  </a>
</div>

# Udemy Project: Travel Site

This is a hands-on project from the Udemy course - [Git a Web Developer Job: Mastering the Modern Workflow](https://www.udemy.com/git-a-web-developer-job-mastering-the-modern-workflow/) by Brad Schiff.
  
# Demo

<div align="center">
  <img src="demo/demo.gif" />
</div>

You can see a complete working example [here](https://hsins.github.io/udemy_Travel-Site/). Or you can run the demo on your local machine, please follow the instructions in [Getting Started](#getting-started).

# Features

- Responsive web design (RWD): mobile-first approach, responsive images (resolution switching / different cropping situations)
- Support for legacy browsers
- Lazy loading images and SVG sprites for faster page loading
- Smooth scrolling to anchor links in header bar
- Revealing contents on scroll
- Classes follow the CSS Architecture with [B.E.M](http://getbem.com/) rules

# Technologies

## Frontend

- [jquery](https://api.jquery.com/)
- [jquery-smooth-scroll](https://github.com/kswedberg/jquery-smooth-scroll)
- [waypoints](http://imakewebthings.com/waypoints/)
- [lazysizes](https://github.com/aFarkas/lazysizes)
- [picturefill](https://github.com/scottjehl/picturefill)
- [normalize.css](http://nicolasgallagher.com/about-normalize-css/)
- [postcss](https://postcss.org/)

## Utils

- [gulp](https://gulpjs.com/)
- [webpack](https://webpack.js.org/concepts/)
- [babel](https://babeljs.io/)
- [browsersync](https://www.browsersync.io/)

Check [`package.json`](https://github.com/Hsins/udemy_travel-site/blob/master/package.json) file for more information.

# Getting Started

Follow the instructions below to set up the environment and run this project on your local machine.

1. Clone this repository.

```bash
# Clone repository
$ git clone https://github.com/Hsins/udemy_Travel-Site.git
```

2. Install dependencies via NPM or Yarn

```bash
# Install dependencies via npm
$ npm install

# Install dependencies via yarn
$ yarn install
```

3. Install gulp globally, run the server and open a browser to visit [http://localhost:3000/](http://localhost:3000/).

```bash
# Install gulp globally via npm
$ npm install gulp -g

# Install gulp globally via yarn
$ yarn install gulp -g

# Run server
$ gulp watch
```

4. Build the deploying files (all the files would be put in the `docs` folder)

```bash
# Build with gulp
$ gulp build

# Preview
$ gulp previewDist
```

# More Information

All the notes I took in [Markdown](https://daringfireball.net/projects/markdown/syntax) (.md) format. You can find them in my [Udemy-Notes](https://github.com/Hsins/Udemy-Notes) repository. The note for this course is [here](https://github.com/Hsins/Udemy-Notes/tree/master/Git%20a%20Web%20Developer%20Job%20Mastering%20the%20Modern%20Workflow).

# License

Licensed under the MIT License.
