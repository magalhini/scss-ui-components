# SCSS UI Components
--

An ongoing library of UI components built using CSS (making use of Sass & Compass). Mostly for fun, mostly for the sake of using the power of CSS to build good looking and (hopefully) useful components.

## Current List
- Toggle Switch (IE9+)
The toggle switch uses nothing more than an input and a label. It automatically generates the correct sizes and distances for all elements based on a given `width` attribute that you pass it in.

#### Usage

A Makefile is provided with a couple of commands that you can use:

`make build` - Compiles the Sass code and generates a regular CSS file under the `css` folder
`make watch` - Runs the Compass watcher, compiling live changes into the CSS files.

Make sure you have Compass install by running `gem install compass` (you may need some `sudo` action if you get any permission errors)
