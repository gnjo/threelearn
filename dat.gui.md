# dat.gui.js usage
```
//pug
//script(src="https://gnjo.github.io/threelearn/dat.gui.js")
  var params = {

				clearPass: true,
				clearColor: 'white',
				clearAlpha: 1.0,

				texturePass: true,
				texturePassOpacity: 1.0,

				cubeTexturePass: true,
				cubeTexturePassOpacity: 1.0,

				renderPass: true
			};


			clearGui();

			function clearGui() {

				if ( gui ) gui.destroy();

				gui = new GUI();

				gui.add( params, "clearPass" );
				gui.add( params, "clearColor", [ 'black', 'white', 'blue', 'green', 'red' ] );
				gui.add( params, "clearAlpha", 0, 1 );

				gui.add( params, "texturePass" );
				gui.add( params, "texturePassOpacity", 0, 1 );

				gui.add( params, "cubeTexturePass" );
				gui.add( params, "cubeTexturePassOpacity", 0, 1 );

				gui.add( params, "renderPass" );

				gui.open();

			}
 ```  
