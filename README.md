# Deploy project

1. Deploy a project
    'npm install'  - install all dependencies
    'gulp sass'
    'gulp pug-html'
Optional :
    'npm install bower' - install bower for libriares, e.g. jquery ( 'bower install jquery' ). All libriares install to /dist


2. Tasks
    'gulp sass' - collect all .sass to style.css
    'gulp min-js' - concat and minify js
    'gulp min-css' - minify css
    'gulp min-image' - compress images
    'gulp px-rem' - convert px to rem
    'gulp watch' - all tasks + run localhost
    'gulp build' - collect all sources to /dist. This task automatically clean the folder before collecting.