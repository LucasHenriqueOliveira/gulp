# Gulp

## Install globally (run from any path)
May require running with admin (sudo on OSX)
`npm install gulp -g`

Gulp in a Nutshell
1. Install gulp globally
2. Create package file
3. Install dependent packages
4. Code your tasks in gulpfile.js

## Create package.json file
Prompts you from author, package name, and basics
`npm init`

`npm install gulp --save-dev (is for development - locally)`
`npm install gulp --save (is for production)`

## Installing package dependencies
`npm install gulp-ng-annotate gulp-jshint --save-dev`

## package.json manages dependencies

```
"devDependencies":{
	"glob": "^4.0.4",
	"gulp-concat": "^2.3.3",
	"gulp-uglify": "^0.3.1",
	"gulp-jshint": "^1.7.1",
	"jshint-stylish": "^0.1.5",
	"gulp": "^3.8.7",
	"gulp-ng-annotate": "^0.3.0"
}
```

`gulp --gulpfile small-gulp.js ngAnnotateTest`
`gulp --gulpfile small-gulp.js hint`
`gulp --gulpfile small-gulp.js watch`

