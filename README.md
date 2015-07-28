## The Maker Network

### Getting Started
The Maker Network is deployed as a static site using Github Pages. That said, in order to work on the project, you'll want to ensure that you have a few tools setup for local development:

- Install [Node.js](http://nodejs.org/)

### To Build
```sh
npm install
```

### To Run The Server
```sh
npm run-script server
```

Now the local preview is avaliable at: http://localhost:8080/ or check the output from 'npm run-script server'.

Note: this is assuming node_modules is under the project root.

### Working on The Maker Network
If changing the css, edit the /less/*.less files then run the script "build.sh" to update compressed .css files, otherwise changes will noot be visible.

### Credits
The origional Maker Map was created by Justin Hileman / hwstartup:
- https://github.com/hwstartup/TheMakerMap.com

