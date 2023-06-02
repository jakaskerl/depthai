Face Detection RGB
==================

This example shows how to run face detection on RGB camera input using SDK. 

For running the same face detection on mono camera, see :ref:`sdk_face_detection_left`.

.. include::  /includes/blocking_behaviour.rst
    


Setup
#####

.. include::  /includes/install_from_pypi.rst

Pipeline
########

.. image:: /_static/images/pipelines/face_detection_color.png
      :alt: Pipeline graph



Source Code
###########

.. tabs::

    .. tab:: Python

        Also `available on GitHub <https://github.com/luxonis/depthai/depthai_sdk/NNComponent/face_detection_color.py>`_.

        .. literalinclude:: ../../../../examples/NNComponent/face_detection_color.py
            :language: python
            :linenos:

.. include::  /includes/footer-short.rst