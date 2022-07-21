===================================
TrackerJack
===================================


What is TrackerJack?
---------------------------------
.. Insert animated gif here

The fast and easy way to export |After Effects| 3d Camera tracked footage including cameras, nulls, and solids into |Blender| as tracked cameras with background footage, vector pointclouds, and planes.

.. |After Effects| raw:: html

   <a href="https://www.adobe.com/products/aftereffects.html", target="_blank">After Effects</a>

.. |Blender| raw:: html

   <a href="https://www.blender.org", target="_blank">Blender</a>
---------------------------------
Why?
---------------------------------
Blender is a fantastic tool with many powerful features for 3D. While it contains a versatile 3d Tracker, it can be very cumbersome and time consuming while Adobe After Effects has a very fast and easy to use 3d Camera Tracker. TrackerJack leverages the power and speed of After Effects, so you can spend most of your time in Blender with modeling, animating, and rendering. 

---------------------------------
How?
---------------------------------
TrackerJack has 2 components - an Adobe After Effects Panel to export the tracked data and a Blender add-on to import the data into your Blender file. 
   #. Track your footage in After Effects. Create nulls and solids as you desire to add details to your scene. Add the Camera information to the TrackerJack Panel and export a JSON file with all of your tracked data.
   #. Use the TrackerJack Import in Blender to create a scene: 
      * All 3d camera details, animation, and background footage attached
      * Scene duration, Framerate, color settings set
      * Tracked points imported as point clouds with editable vertices
      * Solids imported as Mesh Planes
      * All imported items parented to a Empty for easy scaling and rotation.
      * Human Scale mesh created for use in scaling the scene.
      * Simple Compositor setup by default

---------------------------------
Features
---------------------------------

* Uses After Effects Automated 3d Camera Tracking.
* Faster results - spend more time modeling and animating instead of tracking.
* Longer and more complicated tracks.
* Easy to us scene alignment and real world scaling.
* Speed shortcuts like background footage and composition node setup.
* Add additional pointclouds and layers after intital file is built.


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   index
   installation
   quick_start
   panel_options
   
.. note::
   This project is under active development.
   

