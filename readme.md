## Pre installed dependencies ##
Install Node : https://nodejs.org/
Install Bower: `npm install --global bower`

## Getting strated ##
 1. npm install
 2. bower install
 3. Run `gulp serve --dev` to run your app

## Build Task ##
 1. Run `gulp clean` for clean project dir - gulp default action!
 2. Run `gulp build --production`. This will generate production version into 'dist' folder with optimized version.
 3.  After gulp build complete `gulp htmlCopy` . This will copy html without optimized.
 4.  After build `gulp live-serve` This will serve build version.