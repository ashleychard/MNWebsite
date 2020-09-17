# MNWebsite


Project Setup: 

Node 14.9.0
`nvm install 14.9.0`
`nvm use 14.9.0`


For each new page need to install the following dependencies:
* lite-server 2.5.4
    `npm install lite-server@2.5.4 --save-dev`
* Bootstrap 4.5.0
    `npm install bootstrap@4.5.0`
* jQuery 3.5.1 and popper.js 1.16.1
    `npm install jquery@3.5.1 popper.js@1.16.1`
* fontAwesome 5.14.0
    `npm i @fortawesome/fontawesome-free`


Ensure the following items are in the head of the document:
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css" />
    <link rel="stylesheet" href="fontawesome-free-5.14.0-web/css/all.css"/>
    <link rel='stylesheet' href='https://api.mapbox.com/mapbox-gl-js/v1.12.0/mapbox-gl.css' />
    <link rel="stylesheet" href= "css/styles.css">


Ensure the following scripts are added at the end of the body:
<script src="node_modules/jquery/dist/jquery.slim.min.js"><script>
<script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
<script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>

*Note:* For the scripts, and links to the included stylesheets, ensure that they reflect the directory structire properly. 

For example, if you are adding a new file to the HTML folder, add ../ to the beginning.