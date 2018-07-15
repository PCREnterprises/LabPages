# LabPages

## Environment Setup
Install npm using these [setup instructions](https://www.npmjs.com/get-npm)
Install all the npm dependencies by running `npm i`.
Install all the bower dependencies by running `bower install`.
Install gulp - our task runner globally with admin rights by running `npm i -g gulp` or use `sudo npm i -g gulp` if you are using unix based OS.
You are all done.

## Local Development Setup
Run `gulp serve` for a dev server. Navigate to `http://localhost:9000`. The app will automatically reload if you change any of the source files.
For a prod server run `gulp serve:dist`.

## Build
Run `ng build` to build the project. The build files to be served will be stored in the `dist/` directory.
