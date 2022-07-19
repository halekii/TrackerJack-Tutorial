#################
Panel Options
#################

|Video Link|

.. |Video Link| raw:: html

   <a href="https://youtu.be/MNyxm5eU8Sg?t=63" target="_blank">Video Link</a>

After Effects Panel
#################

Create Tab
_________________
:ref:`Install<Installation>` the UI Panel and open After Effects if you haven't already.

    .. image:: images/AE_1_tjpanel.png
        :alt: After Effects TrackerJack Panel
        
Under the Create tab are only two entries to make in order create the initial export of your tracked composition from After Effects to a JSON file that the Blender TrackerJack add-on will import. The values for Focal Length and Angle of View boxes which can be copied from the Camera Settings panel.

#. Double click on the 3D Tracker Camera layer in the comp timeline.
#. Copy the Focal Length value.

     .. image:: images/AE_2_cam_settings_focal.png
        :alt: Camera Settings Focal Length
        
#. Click Cancel to close the panel
#. Paste the value into the TrackerJack Focal Length box.

    .. image:: images/AE_3_tjpanel_focal.png
        :alt: TrackerJack Focal Length


#. Double click on the 3D Tracker Camera layer in the comp timeline.
#. Copy the Angle of View value.

     .. image:: images/AE_4_cam_settings_angle.png
        :alt: Camera Settings Angle of View
        
#. Click Cancel to close the panel
#. Paste the value into the TrackerJack Angle of View box.

    .. image:: images/AE_5_tjpanel_angle.png
        :alt: TrackerJack Angle of View
        
#. Make sure that you have saved your After Effects file.

    .. tip::
        TrackerJack will export the JSON file for Blender to the same location you save your After Effects Project File. When TrackerJack imports your footage into Blender, it first looks for the movie file wherever it was orginally located when imported into After Effects. If the file has moved, it will then look for it in the same folder as the JSON file. The simplist method to avoid issues is to keep your footage file, AE project file, and JSON file in the same folder.

    .. image:: images/pplotter_panel.jpg
        :alt: Perspective Plotter Panel

#. Click the button *Plot Perspective*. The button will now say *Plotting...*. The camera will adjust to a default position with the perspective line control points ready to be adjusted.

    .. image:: images/pplotter_panel_plotting.jpg
        :alt: Perspective Plotter Panel

#. These perspective lines allow you to align the camera to different vanishing points.  Left-Click and drag on the ends of these axes to manipulate them.  There is a pair of control axes for each vanishing point.  By default, you will be in :ref:`two-point perspective<Two-Point Mode>` mode:
