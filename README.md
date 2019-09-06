Parts.io Hardware Icons
=========
http://supplyframe.github.io/font-demo/
### Installation ###

1. Fork the repo into your account and clone it from there
2. Include Font Custom CSS in project `<link href="path/to/fontcustom/fontcustom.css" rel="stylesheet">`

### To make changes to SVG and compile font: ###

```Locate the appropriate svg project name that contains the font files you wish to alter.```
1. Install FontCustom http://fontcustom.com/
2. Run `fontcustom watch /path/to/vectors` (continuous watch) or `fontcustom compile /path/to/vectors` (single compile)
3. Alternatively, you can just `cd` into the `svg` folder and run `fontcustom compile`.
4. Once new `.ttf` `.svg` `.woff` `.eot` `woff2` files have been generated, you must rename all the file names to `fcl-v1-icon-font` while still maintaining their respective file types (`.ttf` `.svg` `.woff` `.eot` `woff2`).
5. A `.css` file will also be generated. You will have to convert the contents of that `.css` file to `.scss` format.
6. Rename that new `.scss` file to `_fonts.scss`.
7. Place all of those freshly generated (and renamed) files into their respective places in the project directory of your intended project.
8. Remember to commit your changes.
