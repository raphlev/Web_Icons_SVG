# grunticon and grumpicon

grunticon is a Grunt.js task that makes it easy to manage icons and background images for all devices, preferring HD (retina) SVG icons but also provides fallback support for standard definition browsers, and old browsers alike. From a CSS perspective, it's easy to use, as it generates a class referencing each icon, and doesn't use CSS sprites.

grunticon takes a folder of SVG/PNG files (typically, icons that you've drawn in an application like Adobe Illustrator), and outputs them to CSS in 3 formats: svg data urls, png data urls, and a third fallback CSS file with references to regular png images, which are also automatically generated and placed in a folder.

grunticon also generates a small bit of JavaScript to drop into your site, which asynchronously loads the appropriate icon CSS depending on a browser's capabilities, and a preview HTML file with that loader script in place.

You can see a demonstration of the output here.
..
..
https://github.com/filamentgroup/grunticon

Drag & Drop ur SVGs on the Grumpicon
..
..
http://www.grumpicon.com/

# Execute this command to avoid Windows execution issue first

Set-ExecutionPolicy Unrestricted

# Install

npm install

# Execute

grunt

# Update a file in /socialmedia/SVG_raw

This should minify all svg files from SVG_raw to SVG_optim folder
This should copy svg css inline in index.html

https://www.linkedin.com/learning/creating-web-icons-with-svg/display-grunticon-svg-icons-in-html-documents?u=76815018
Chapter 5.5
