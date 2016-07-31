# Gulp Watch & Live Reload

## Set up a server

+ Add new module called static server
+ or npm install static-server@2.0.0 --save (not save-dev, we need it in production server)
+ Set up server.js file
+ Run server.js in terminal

## Gulp Watch

+ Gulp watch will watch changes in a folder, and run gulp task you specify
+ But it's not like live server, it will not automaticcly reload your browswer
+ Gulp watch is built in to gulp, live reload is not

## Live reload

+ Run ``npm install gulp-livereload@3.8.1 --save-dev`` to install it
+ Install chrome livereload plugin or add a script to your html
