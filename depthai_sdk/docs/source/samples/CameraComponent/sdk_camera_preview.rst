Camera Preview
==============

This example shows how to set up a pipeline that outputs a a preview for color camera, both mono cameras and their stereo depth. Each frame is displayed using OpenCV in blocking behavour. 

.. include::  /includes/blocking_behaviour.rst

Demo
####



Setup
#####

.. include::  /includes/install_from_pypi.rst

Pipeline
########

.. image:: /_static/images/pipelines/camera_preview.png
      :alt: Pipeline graph



Source Code
###########

.. tabs::

    .. tab:: Python

        Also `available on GitHub <https://github.com/luxonis/depthai/depthai_sdk/examples/CameraComponent/camera_preview.py>`__

        .. literalinclude:: ../../../../examples/CameraComponent/camera_preview.py
            :language: python
            :linenos:

.. include::  /includes/footer-short.rst