# NPM Package Installs

_This file includes all the commands we've been using to set up JS projects. Just copy paste each code block into your terminal in the new project root directory, including the newline after the group of commands._

## First
```
npm init
 
```
_Hit enter until complete_

## Basic packages

```
npm install gulp --save-dev
npm install browserify --save-dev
npm install vinyl-source-stream --save-dev
npm install gulp-concat --save-dev
npm install gulp-uglify --save-dev
npm install gulp-util --save-dev
npm install del --save-dev
npm install jshint --save-dev
npm install gulp-jshint --save-dev
npm install babelify babel-preset-es2015 --save-dev
 
```

## Bower/Server packages

```
npm install bower -g
bower init












```
_Type "y" and enter._
```
bower install jquery --save
bower install materialize --save
npm install bower-files --save-dev
npm install browser-sync --save-dev
 
```

## Test Packages

```
npm install jasmine --save-dev
./node_modules/.bin/jasmine init
npm install watchify --save-dev
npm install karma --save-dev
npm install karma-jasmine jasmine-core --save-dev
npm install karma-chrome-launcher --save-dev
npm install karma-cli --save-dev
npm install karma-browserify --save-dev
npm install karma-jquery --save-dev
npm install karma-jasmine-html-reporter --save-dev
npm install -g karma-cli
```
_Hit enter many times_
```
karma init
```
_Hit enter many times_
## After setting up tasks in gulpfile.js

```
gulp build
 
```
set package.json "test" to "nyc karma start karma.conf.js istanbul"

copy gulpfile.js to project

copy karma.config file to project 
