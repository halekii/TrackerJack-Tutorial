#################
Quick Start
#################

|Video Link|

.. |Video Link| raw:: html

   <a href="https://youtu.be/MNyxm5eU8Sg?t=63" target="_blank">Video Link</a>
   
After Effects
#################

#. Install After Effects Effects Panel
   * Install TrackerJack_AE.jsxbin to your After Effects ScriptUI Panels folder and :ref:`install<After Effects Panel Install>` if you haven't already.  (After Effects > Scripts > ScriptUI Panels)
   * Open After Effects, and launch the TrackerJack Panel via the Windows Menu (Windows > TrackerJack_AE.jsxbin)

    .. image:: images/AE00-Install.gif
        :alt: Install AE Panel
        
#. Add footage and Track
   * Add footage and create a composition.
   * Use Effects > 3D Camera Tracker on the footage layer in your composition.

    .. image:: images/AE01-Import.gif
        :alt: Import and Track Footage
        
#. Select tracked points and create elements
   * Select points and right click to create Origin and Ground
   * Right click to create Solid and Camera.
   * Select additional points to create additional nulls and solids as desired.

    .. image:: images/AE02-AddItems.gif
        :alt: Add AE Items
        
#. Using the TrackerJack Panel
   * Enter the Camera information on the TrackerJack panel
   * Save the After Effects file.
   * Click the Export JSON button on the TrackerJack Panel

    .. image:: images/AE03-Export.gif
        :alt: Export JSON
    .. tip::
        "Allow scripts to write files and access network" must be enabled in AE Preferences.



Blender
#################
#. Install the Addon if you haven't already
   * Open Blender and :ref:`install<Blender Add-on Install>.
   * Locate the TrackerJack zip file
   * Enable the check box to activate the add-on

    .. image:: images/BL00-Install.gif
        :alt: Install Blender Add-on

#. Import the JSON data into Blender

   * Press 'a' to select all, then press 'x' and click the *Delete* button to clear the default elements.
   * Go to the File menu and select *TrackerJack AE Tracking Data (.json)* listed by selecting the import command.
   * Locate and select the JSON file exported from After Effects. (Adjust settings of panel or use default settings)

    .. image:: images/BL01-Import.gif
        :alt: Import JSON data
        
#. Scale and Rotate the World

   * Press '0' to switch to the Camera view, or go to *View* -> *Cameras* -> *Active Camera*.
   * Press Spacebar to play the timeline (Advancing frames)
     will update the scene if your pointclould doesn't seem to be aligned.
   * Select the "World" empty in the Scene Outiner
   * Press 's' and adjust the scale so the "Human Scale" mesh matches the scale for your scene.
   * Press 'r' then 'z' and adjust the z rotation so the grid matches your scene.

    .. image:: images/BL02-ScaleandRotate.gif
        :alt: Scale and Rotate the World
      
#. Adding Additional Items

    .. image:: images/BL03-AdditionalItemsAE.gif
        :alt: Scale and Rotate the World

    .. image:: images/BL04-AdditionalItemsBlender.gif
        :alt: Scale and Rotate the World
