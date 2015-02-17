# Lazy THREE.js Sublime Completions
Fast THREE.js Sublime Text completions for the fatigued typist.

![Animated gif showing completions](http://i.imgur.com/WPlkran.gif)

Install
=============
Place the threejsfast.sublime-completions into your Sublime Text 3/Packages/User folder

The following keywords will generate the following when hitting tab...

Mesh
-------------
    new THREE.Mesh( geometry, material );

Group
-------------
    new THREE.Group();

Geometry
-------------
    new THREE.Geometry();

Box
-------------
    new THREE.BoxGeometry( width, height, depth, 1, 1, 1 );

Sphere
-------------
    new THREE.SphereGeometry( radius, 8, 6 );

Plane
-------------
    new THREE.PlaneGeometry( width, height, 1, 1 );

.add
-------------
    .add( child );

.traverse
-------------
    .traverse( function( o ){

    });

Phong
-------------
    new THREE.MeshPhongMaterial( options );

MatOpts
-------------
    {
      color: 0xffffff,
      specular: 0xffffff,
      shininess: 30,
      map: undefined,
    }

loadTexture
-------------
    THREE.ImageUtils.loadTexture( filepath );

0xfff
-------------
    0xffffff

Color
-------------
    new THREE.Color( hex );


Extreme Lazy Mode
=============

makeView
-------------
    function viewFunc( args ){
      var view = new THREE.Group();
      return view;
    }

MakeMesh
-------------
   var nameGeometry = new THREE.typeGeometry();
   var nameMaterial = new THREE.typeMaterial();
   var nameMesh = new THREE.Mesh( nameGeometry, nameMaterial );

MakeBox (plane, sphere etc)
-------------
  var box = new THREE.Mesh( new THREE.BoxGeometry( width, height, depth, 1, 1, 1 ), new THREE.MeshPhongMaterial( { color: color } ) );