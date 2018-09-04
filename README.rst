
.. image:: https://github.com/mehranyarahmadi/MCRT/blob/master/Download_Button.png
   :target: https://doi.org/10.5281/zenodo.1407154
********************
`2D Monte Carlo Ray Tracing`_
********************
.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.1407187.svg
   :target: https://doi.org/10.5281/zenodo.1407154

.. _TensorFlow World: http://tensorflow-world.readthedocs.io/en/latest/

This repository aims to provide simple and ready-to-use tutorials for Monte Carlo Ray Trace Method applied in Radiation Heat Transfer.

.. image:: https://github.com/mehranyarahmadi/MCRT/blob/master/Cover.jpg?raw=true

#################
Table of Contents
#################
.. contents::
  :local:
  :depth: 3

============
Motivation
============

In the absence of a participating medium, the radiation distribution factor 𝐷𝑖𝑗 is defined as the fraction of the power emitted by surface element 𝑖 that is absorbed by surface element 𝑗, due both to direct radiation and to all possible reflections [1]. Note that this is not the same entity as the purely geometrical configuration factor 𝐹𝑖𝑗, defined as the fraction of diffusely distributed power leaving (emitted plus reflected) surface i and arriving at (but not necessarily absorbed by) surface j by direct radiation only. The configuration factor is central to the net-exchange, or radiosity-irradiance, method, while the distribution factor lies at the heart of the Monte Carlo ray-trace (MCRT) method.

~~~~~~~~~~~~~~~~~~~~~
Why use Monte Carlo Ray Trace?
~~~~~~~~~~~~~~~~~~~~~

A significant advantage of the MCRT method over the net-exchange method is that the models for surface behavior (emissivity, absorptivity, and reflectivity) can be directional, in which case 𝜀𝑖 in Eq. (1) is the hemispherical emissivity, with directionality effects being accounted for by the distribution factors. Then it may be said that the MCRT method provides an approximate solution to an exact (bidirectional) exchange model, while the net-exchange method provides an exact solution to an approximate (diffuse-specular) exchange model.

=================================================
Installation and Setup the Environment
=================================================

---

====================
Tutorial on Monte Carlo Ray Trace
====================

---

=============
Contributing
=============

---

~~~~~~~~~~~
Final Note
~~~~~~~~~~~

---

================
Acknowledgement
================

---
