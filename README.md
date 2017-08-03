## Gulp boilerplate

This is a simple gulp workflow boilerplate to
- Start a web server and reload browser on change
- Compile SCSS to CSS and inject CSS into the browser
- Compile ES6 to ES5

For production, this includes
- Image optimization
- CSS minification
- JS Uglify

### Getting started

1. Open your terminal and type `git clone git@github.com:abialbon/gulp-boilerplate.git <folder-name>`
2. Run `npm install`
3. Add HTML to `index.html`
4. Add SCSS to `SCSS` folder
5. Add images `images` and fonts to `fonts` folder
6. To start the serve: `npm start`

The browser will open and reload automatically. If you need to view your porject on multiple devices, you can use the external link to open the project in any device connected to the same wifi network.

### For production

Use `npm build`

Your project will compile to the `dist` folder.