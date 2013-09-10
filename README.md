lol
===

working
{
  "name": "mygamename",
  "version": "0.0.1",
  "dependencies": {
    "voxel-hello-world": "0.6.0"
  }
}
       
$ npm install
          
var createGame = require('voxel-hello-world')
var game = createGame()
          
$ npm install browserify -g
$ browserify mygame.js -o builtgame.js
    <!doctype html>
<html>
  <body>
    <script src="builtgame.js"></script>
  </body>
</html>   
