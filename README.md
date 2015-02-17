# threesublimecompletions
Quick completions for THREE.js Sublime Text

![Animated gif showing completions](http://i.imgur.com/WPlkran.gif)

Place the threejsfast.sublime-completions into your Sublime Text 3/Packages/User folder

Mesh
-------------
    new THREE.Mesh( geometry, material );

Object3D
-------------
    new THREE.Object3D();

Geometry
-------------
    new THREE.Geometry();

Box
-------------
    new THREE.BoxGeometry( width, height, depth, 1, 1, 1 );

Plane
-------------
    new THREE.PlaneGeometry( width, height, 1, 1 );

.add
-------------
    .add( child );

Phong
-------------
    new THREE.MeshPhongMaterial({
      color: color
    });

Material
-------------
    new THREE.MeshBasicMaterial({
      color: color
    });

0xfff
-------------
    0xffffff

Color
-------------
    new THREE.Color( hex );

makeView
-------------
    function viewFunc( args ){
      var view = new THREE.Object3D();
      return view;
    }",