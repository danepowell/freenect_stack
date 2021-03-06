Change history
==============

0.2.1 (05/21/2013)
------------------

 * Groovy release update
 * Fixed nodelet description file installation (`#5`_)
 * Fixed problem with streaming on a cold start of the machine (`#3`_)
 * Minor CMake cleanup

0.2.0 
-----

 * Convert to catkin (`#2`_)
 * libfreenect is now released as a separate 3rd-party CMake package,
   no longer contained here.

0.1.1
-----

 * Fuerte release update.
 * Fixed issue `#8`_.
 * Launch file improvements while using tf_prefix. Now there is a
   clear separation between namespace and tf_prefix.

0.1.0
-----

 * Fuerte release.
 * Fixed USB 3.0 Issue. Precise (Ubuntu 12.04) users will have to
   update their Kernel to 3.4.1 or higher to enable USB 3.0 support.
 * Added diagnostics support to freenect_camera.
 * Enabled launching the driver under a supplied namespace.
 * Added a parameter to enable libfreenect debug messages.
 * Launch file improvements in freenect_launch and more examples.

0.0.3
-----

 * Fixed symbolic links in libfreenect ROS wrapper. This prevented the
   system install from working.

0.0.2
-----

 * freenect_stack reorganized and released for ROS Fuerte.

.. _`#2`: https://github.com/ros-drivers/freenect_stack/issues/2
.. _`#3`: https://github.com/ros-drivers/freenect_stack/issues/3
.. _`#5`: https://github.com/ros-drivers/freenect_stack/issues/5

.. _`#8`: https://github.com/piyushk/freenect_stack/issues/8
