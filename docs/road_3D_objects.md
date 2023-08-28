
# Road 3D objects

* Export wavefront(*.obj)
* This will provide multiple files
* `road.obj`: An OBJ file (*.obj) contains information about the geometry of 3D objects.
* `road.mtl`: The MTL file is a library containing one or more named material definitions and settings.
  * `MTL`: Material Template Library from Wavefront Technologies
* `<multiple>.png`: multiple png files are created for road.
  * Asphalt1 
  * Concrete1
  * LaneMarking1
  * Signals_TextureSheet01
* Each files has three variants:  `*.Diff.png`; `*_Norm.png`; `*_Spec.png`;
  * E.g. Asphalt1_Diff.png, Asphalt1_Norm.png, Asphalt1_Spec.png.
* For object added, the 3D object are created with front and back image
  * Sign_R1-1-Back.png
  * Sign_R1-1.png
* This can be used in simulation. E.g. In CM Scenario Editor, Terrain generation, Filename: browse to *.obj file.
* `NOTE`: The sized files shoudl be in same path as *.obj files.
