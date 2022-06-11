#################
Quick Start
#################

|Video Link|

.. |Video Link| raw:: html

   <a href="https://youtu.be/MNyxm5eU8Sg?t=63" target="_blank">Video Link</a>

#. Install TrackerJack_AE.jsxbin to your After Effects ScriptUI Panels folder and :ref:`installation<After Effects Panel Install>` if you haven't already.  (After Effects > Scripts > ScriptUI Panels)
#. Open After Effects, and launch the TrackerJack Panel via the Windows Menu (Windows > TrackerJack_AE.jsxbin)

    .. image:: images/AE00-Install.gif
        :alt: Import and Track Footage
        
#. Add footage and create a composition.
#. Use Effects > 3D Camera Tracker on the footage layer in your composition.

    .. image:: images/AE01-Import.gif
        :alt: Import and Track Footage
        
#. Select points and right click to create Origin and Ground
#. Right click to create Solid and Camera.
#. Select additional points to create additional nulls and solids as desired.

    .. image:: images/AE02-AddItems.gif
        :alt: Import and Track Footage
        
#. Enter the Camera information on the TrackerJack panel
#. Save the After Effects file.
#. Click the Export JSON button on the TrackerJack Panel

    .. image:: images/AE03-Export.gif
        :alt: Import and Track Footage
    .. tip::
        "Allow scripts to write files and access network" must be enabled in AE Preferences.
        
#. Open Blender and :ref:`installation<Blender Add-on Install>` the add-on if you haven't already.
#. Press '0' to switch to the Camera view, or go to *View* -> *Cameras* -> *Active Camera*.
#. Press the 'n' key to open the viewport's side tabs if they are not visible already.

    .. image:: images/properties_tabs.jpg
        :alt: Properties Tab

#. Go to the tab called *P.Plotter* (it will only be there if you are looking through the camera).



#. Click the button *Plot Perspective*. The button will now say *Plotting...*. The camera will adjust to a default position with the perspective line control points ready to be adjusted.

#. These perspective lines allow you to align the camera to different vanishing points.  Left-Click and drag on the ends of these axes to manipulate them.  There is a pair of control axes for each vanishing point.  By default, you will be in :ref:`two-point perspective<Two-Point Mode>` mode:

    .. tip::
        See the :ref:`tips<Setting up perspective lines>` section for setting up perspective lines optimally.

#. You can now choose to :ref:`set up a background<Match Background>` image or video, change the :ref:`parameters<parameters>` to your needs, switch to Blender's |quad view| or use |multiple viewports|. Once you're happy, click the **"Plotting..."** button again to switch the tool off. Your camera settings will be remembered for next time.

.. |quad view| raw:: html

   <a href="https://docs.blender.org/manual/en/latest/editors/3dview/navigate/views.html", target="_blank">quad view</a>



.. |multiple viewports| raw:: html

   <a href="https://docs.blender.org/manual/en/latest/interface/window_system/areas.html", target="_blank">multiple viewports</a>

