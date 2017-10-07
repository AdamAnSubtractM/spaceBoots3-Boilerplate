spaceBoots3
=========

### spaceBoots3 is a Sass-based responsive CSS framework built on mySpaceBase and Bootsrap 3.


## Getting Started
```sh
1. $ git clone https://user-name@bitbucket.org/dsgfed/spaceBoots3.git
2. $ npm i
3. $ gulp launch
```
4. Work out of the 'src' directory directly
5. Open scss/_vars.scss to make changes to your global variables
6. Start building out your HTML. I've included index.html as a starting point
7. scss/bootstrap4/ is the core of spaceBoots3
8. Do a find and replace on the entire project directory for '.spaceBootsWrap' and replace the name with your project specfic name (e.g. '.gameCrusher3' )

## Super Important:

* Bootstrap4 is in beta and is built on flex whereas Bootstrap3 is buit on floats. For that reason you likely are going to want to use my build call spaceBoots3 which is built off of Bootstrap 3 IF you're going to be using this as a project for DSG, FnS, or GGXY. 
* Bootstrap3 and the compiler do a great job at keeping this pretty lightweight despite all of the power behind it. However, if you're not using anything but the bootstrap grid system, please only import the grid system.
* I made it super easy to use just the grid. When you clone this switch run this cmd:
```sh
git checkout grid-only
```

Many CSS frameworks are meant to be included and left alone. But spaceBoots3 is a boilerplate layer that can be built upon and tailored for your needs. It combines best practices for today’s responsive web with the core components we use on every project. Not to mention Bootstrap4. Consider it the launch pad for your adventures into cyberspace.

spaceBoots3:
[![Build Status](https://img.shields.io/travis/space150/spaceBase.svg?style=flat-square)](https://travis-ci.org/space150/spaceBase)

### Highlights

* Bootsrap 3
* Object-oriented CSS
* Optimized for light speed
* Built on REMs, with px fallback
* Supports modern browsers including IE9+

### Customizable Features

* Compatible with any Sass 3.3 compiler
* Scalable, mobile-first grid - choose how robust you want it
* Base font size for mobile vs desktop
* Global variables for breakpoints, colors, fonts and more

Your editor can be setup with EditorConfig so that code style standards are enforced automatically. See http://editorconfig.org/#download and install the plugin for your editor of choice.

## The spaceBoots3 folder structure:

Read the [CSS Architecture Overview](src/scss/README.md) for documentation of the SCSS files.

```
Build in the src directory. 

src/
  assets/
    fonts/
    images/
    media/
scss/
  bootstrap3/
    bootstrap/
    _bootstrap3.scss
  _manifest.scss
  _vars.scss
  app.scss
css/
  app.css
js/
  bootstrap.js
  scripts.js
```

You can remove:
- `bower.json`
- `Gemfile`
- `Gemfile.lock`
- `Rakefile`
- `test/`
(If you download the original)

## Credits

* [Adam Knee] (http://adamknee.net/)
* [Sass MQ](https://github.com/sass-mq/sass-mq)
* [Bootstrap](http://getbootstrap.com)

## License

spaceBoots3 is free to use under the [MIT License](LICENSE.md).

Copyright 2017 [Adam Knee](http://www.adamknee.net)
