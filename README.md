# starter
1. npm init - add the package.json

2. First install - 
npm install node-sass --save-dev

3. create sass folder

4. create sass files: main.scss

5. take all the css code and put it into the main.scss

6. add npm script to package.json - using the  - node-sass and the input file- sass/main.scss output file - css/style.css

	  "scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css" 
  }

 7. in terminal: npm run compile:sass

 8. add to watch changes -  "compile:sass": "node-sass sass/main.scss css/style.css -w" 

 9. npm install live-server -g (install globally). from home server in terminal: live-server. if necessary you can change the local server.

 10. full grid and layouts, flexible/responsive images, media queries

 - layout types - float, flex, css grid
