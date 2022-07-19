#################
Panel Options
#################

|Video Link|

.. |Video Link| raw:: html

   <a href="https://youtu.be/MNyxm5eU8Sg?t=63" target="_blank">Video Link</a>

After Effects Panel
#################
:ref:`Install<Installation>` the UI Panel and open After Effects if you haven't already.

    .. image:: images/AE_1_tjpanel.png
        :alt: After Effects TrackerJack Panel
        
There are only two entries to make in order to export your camera tracked composition from After Effects to a JSON file that the Blender TrackerJack add-on will import. The Focal Length and Angle of View which
can be copied from the Camera Settings panel.

#. Double click on the 3D Tracker Camera layer in the comp timeline.
#. Copy the Focal Length value.

     .. image:: images/AE_2_cam_settings_focal.png
        :alt: Camera Settings Focal Length
        
#. Click Cancel to close the panel
#. Paste the value into the TrackerJack Focal Length box.

    .. image:: images/AE_3_tjpanel_focal.png
        :alt: TrackerJack Focal Length

#. Go to the tab called *P.Plotter* (it will only be there if you are looking through the camera).

    .. image:: images/pplotter_panel.jpg
        :alt: Perspective Plotter Panel

#. Click the button *Plot Perspective*. The button will now say *Plotting...*. The camera will adjust to a default position with the perspective line control points ready to be adjusted.

    .. image:: images/pplotter_panel_plotting.jpg
        :alt: Perspective Plotter Panel

#. These perspective lines allow you to align the camera to different vanishing points.  Left-Click and drag on the ends of these axes to manipulate them.  There is a pair of control axes for each vanishing point.  By default, you will be in :ref:`two-point perspective<Two-Point Mode>` mode:
