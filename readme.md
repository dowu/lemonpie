# Lemonpie

Lemonpie is a tiny **SCSS base package**. It contains frequently used **variables**, **mixins** to optimize workflows as well as a **browser reset**. You can use all of them together by importing ``lemonpie.scss`` or you can import single files.


## Installation

To install the Lemonpie package, just hit the following in your terminal:

```bash
$ npm install lemonpie
```

## Configuration

The configuration depends on what you need. Import ``lemonpie.scss`` in **your main SCSS file** with the line below for the whole experience.

```css
@import "~node_modules/lemonpie/lemonpie.scss";
```

Another possibility is to import each file for it's own in **your main SCSS File**. This should look like the following:

```css
@import "reset";
@import "variables"; /* needs functions to work */
@import "mixins"; /* needs variables to work */
@import "functions"; 
@import "typo";
```

> Don't forget to import the SCSS dependencies for some files. They won't work otherwise.

## Author

Dominik ([Twitter](https://twitter.com/wurmdo), [GitHub](https://github.com/dowu))