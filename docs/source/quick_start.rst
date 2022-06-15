#################
Quick Start
#################

|Video Link|

.. |Video Link| raw:: html

   <a href="https://youtu.be/MNyxm5eU8Sg?t=63" target="_blank">Video Link</a>
   
After Effects
#################

#. Install TrackerJack_AE.jsxbin to your After Effects ScriptUI Panels folder and :ref:`installation<After Effects Panel Install>` if you haven't already.  (After Effects > Scripts > ScriptUI Panels)
#. Open After Effects, and launch the TrackerJack Panel via the Windows Menu (Windows > TrackerJack_AE.jsxbin)

    .. image:: images/AE00-Install.gif
        :alt: Install AE Panel
        
#. Add footage and create a composition.
#. Use Effects > 3D Camera Tracker on the footage layer in your composition.

    .. image:: images/AE01-Import.gif
        :alt: Import and Track Footage
        
#. Select points and right click to create Origin and Ground
#. Right click to create Solid and Camera.
#. Select additional points to create additional nulls and solids as desired.

    .. image:: images/AE02-AddItems.gif
        :alt: Add AE Items
        
#. Enter the Camera information on the TrackerJack panel
#. Save the After Effects file.
#. Click the Export JSON button on the TrackerJack Panel

    .. image:: images/AE03-Export.gif
        :alt: Export JSON
    .. tip::
        "Allow scripts to write files and access network" must be enabled in AE Preferences.
        
Blender
#################
#. Open Blender and :ref:`installation<Blender Add-on Install>` the add-on if you haven't already.

    .. image:: images/BL00-Install.gif
        :alt: Install Blender Add-on

#. Import the JSON data into Blender

   * Press 'a' to select all, then press 'x' and click the delet button to clear the default elements.
   * Go to the File menu and select "TrackerJack AE Tracking Data (.json)" via the import command.
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
      
       
#. Click the button *Plot Perspective*. The button will now say *Plotting...*. The camera will adjust to a default position with the perspective line control points ready to be adjusted.

#. These perspective lines allow you to align the camera to different vanishing points.  Left-Click and drag on the ends of these axes to manipulate them.  There is a pair of control axes for each vanishing point.  By default, you will be in :ref:`two-point perspective<Two-Point Mode>` mode:

    .. tip::
        See the :ref:`tips<Setting up perspective lines>` section for setting up perspective lines optimally.

#. You can now choose to :ref:`set up a background<Match Background>` image or video, change the :ref:`parameters<parameters>` to your needs, switch to Blender's |quad view| or use |multiple viewports|. Once you're happy, click the **"Plotting..."** button again to switch the tool off. Your camera settings will be remembered for next time.

.. |quad view| raw:: html

   <a href="https://docs.blender.org/manual/en/latest/editors/3dview/navigate/views.html", target="_blank">quad view</a>



.. |multiple viewports| raw:: html

   <a href="https://docs.blender.org/manual/en/latest/interface/window_system/areas.html", target="_blank">multiple viewports</a>

