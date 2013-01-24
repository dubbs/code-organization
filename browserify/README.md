## BUILD (development)
browserify main.js -wo build.js

## MINIFY (deploy)
uglifyjs -nc -o build.min.js build.js
