.. _render:

==========
Raytracing
==========

Image rendering is performed via a C++ GPU-accelerated raytracer. Much of the original code structure was developed with the help of `Accelerated Ray Tracing in One Weekend with CUDA <https://developer.nvidia.com/blog/accelerated-ray-tracing-cuda/>`_ though various additions and alterations have been made to suit the specific purpose of planetary ray tracing.

Key components to the raytracing methology are listed below

.. cpp:class:: Ray
