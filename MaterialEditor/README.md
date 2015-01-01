Babylon JS Material Editor v 0.9
================================

An AngularJS based typescript project for real-time in browser material editing using BabylonJS (http://babylonjs.com)
This is the first release of the material editor, with a simple UI using twitter's bootstrap.

Demo
-------

http://my-cac.com/materialEditor

About the code
----------
The typescript files are located at MaterialEditor.

Vendor contains external libraries which I used:
* BabylonJS https://github.com/BabylonJS/Babylon.js
* Angular Color Picker https://github.com/buberdds/angular-bootstrap-colorpicker
* Angular Slider directive https://github.com/PopSugar/angular-slider

application.js is a rendered javascript from the typescript source. Generated by Visual Studio 2013.

Roadmap V.1
----------------------
* ~~Exporting the material as javascript / babylonjs material~~ - Done
* ~~Allow uploading the canvas images to a server~~ - Done (No CubeTexture Support at the moment)
* ~~New UI~~ - Done
* ~~Change light properties~~ - Done
* ~~Adaptation to BabylonJS 2.0~~ - Done
* ~~Upload your own object~~ - Done
* ~~Multimaterial support~~ - Done
* ~~Supporting further types of textures (like mirror)~~ - Done : Mirror supported.
* ~~Support cube projection for reflections~~ - Done

Roadmap V.2
--------------------------
* Video support
* Shaders / Effects
* ~~Displacement maps~~ - Possible but will not be done at the moment. This is actually a change of the geometry. Maybe in future versions.


MIT License
------------------

Copyright (c) 2014-2015 Raanan Weber (raananw@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.