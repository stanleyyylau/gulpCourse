# Your first gulp task

## NPM & package.json

+ Don't install gulp in the public folder, it's gonna be to be served to the browser
+ run ``npm init`` on your folder, you'll get package.json file (you can create this file on your own)


## Installing gulp locally & gulpfile.js

+ Install gulp one more time locally ``npm install gulp --save``
+ You can delete node_modules folder and redownload it by running ``npm install``
+ Create a file called ``gulpfile.js`` in the root folder (name is important)


## Crateing your first gulp tasks

+ Break tasks into smaller pieces
+ Run ``gulp TASKNAME`` will triggar the gulp task
+ Run ``gulp`` will trggar the default task


## Your first Gulp plugin

+ Install gulp uglify with --save-dev  flag
+ Dependencies and devDependencies (gulp should be in devDependencies, paste it to your package.json file and delete dependencies object)
+ Go to gulp.js to find your plugins
