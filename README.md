## Gulp Setup - Preparing the enviroment to work with Gulp.

Note: I learned to do all things in this repository with [DorianDesigns](https://github.com/DorianDesings/gulp-2020/tree/master/public)

## Documentation

#### Installing Gulp-CLI globaly in you machine

```bash
npm install --global gulp-cli
```
If do you utilize GULP, jump this step

#### Every project you'll execute this steps

```bash
1 - npm install --global gulp-cli
2 - npm install --save-dev gulp
3 - npm install --save-dev @babel/core @babel/register @babel/preset-env
```

##### Cation: You must create files for settings in your root project

```bash
touch .babelrc // You will put the Babel Settings
touch gulpfile.babel.js //  You will write thethe all settings of Gulp (tasks, watchers, etc)
```

### Components

#### JavaScript

##### gulp-babel - to convert javaScript code in ES5

```bash
npm install --save-dev gulp-babel
```

##### gulp-terser - It's the new version of 'uglify', for minify the JavaScript code

```bash
npm install --save-dev gulp-terser
```

##### gulp-concat - Join all javascript files in only one

```bash
npm install --save-dev gulp-concat
```

#### HTML

##### gulp-htmlmin - Minify your HTML

 - For more info and settings see: [HTMLMinifier Documentation](https://github.com/kangax/html-minifier)

```bash
npm install --save gulp-htmlmin
```

#### CSS

```bash
npm install --save-dev gulp-postcss cssnano autoprefixer
```

- Note: For use the 'autoprefixer' you have two options: 
```
1 - Put in your package.json file  all browsers that you want to give support;
2 - Create a file called '.browserslistrc' and put that browser list.

//[PostCSS Documentation Documentation](https://github.com/postcss/postcss/blob/master/docs/plugins.md)
```


##### gulp-htmlmin - Minify your HTML

```bash
npm install --save gulp-htmlmin
```

#### PUG

```bash
npm install --save-dev gulp-pug
```

#### SASS

```bash
npm install --save-dev gulp-sass
```

#### Helpers

##### Clean Cache with Cache Bust

```bash
npm install --save-dev gulp-cache-bust
```

##### Compress Image with Imagemin

```bash
npm install --save-dev gulp-imagemin
```

##### Browser Sync

```bash
npm install --save-dev browser-sync
```

##### Plumber

```bash
npm install --save-dev gulp-plumber
```