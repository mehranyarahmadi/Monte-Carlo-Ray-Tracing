
.. image:: https://github.com/mehranyarahmadi/MCRT/blob/master/Download_Button.png
   :target: https://doi.org/10.5281/zenodo.1407154
********************
`An Engine for Analyzing 2D Radiation Heat Transfer Monte Carlo Ray Tracing`_
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

In the absence of a participating medium, the radiation distribution factor 𝐷𝑖𝑗 is defined as the fraction of the power emitted by surface element 𝑖 that is absorbed by surface element 𝑗, due both to direct radiation and to all possible reflections. Note that this is not the same entity as the purely geometrical configuration factor 𝐹𝑖𝑗, defined as the fraction of diffusely distributed power leaving (emitted plus reflected) surface i and arriving at (but not necessarily absorbed by) surface j by direct radiation only. The configuration factor is central to the net-exchange, or radiosity-irradiance, method, while the distribution factor lies at the heart of the Monte Carlo ray-trace (MCRT) method.

~~~~~~~~~~~~~~~~~~~~~
Why use Monte Carlo Ray Trace?
~~~~~~~~~~~~~~~~~~~~~

A significant advantage of the MCRT method over the net-exchange method is that the models for surface behavior (emissivity, absorptivity, and reflectivity) can be directional, in which case 𝜀𝑖 in Eq. (1) is the hemispherical emissivity, with directionality effects being accounted for by the distribution factors. Then it may be said that the MCRT method provides an approximate solution to an exact (bidirectional) exchange model, while the net-exchange method provides an exact solution to an approximate (diffuse-specular) exchange model.

====================
Tutorial on Monte Carlo Ray Trace
====================

In the MCRT method, the distribution factor matrix is populated by tracing a large number of rays as they navigate within an enclosure subject to the rules of geometrical optics, which treat the surface absorptivities and reflectivities as probabilities. Use of distribution factors in radiation analysis requires that the enclosure be subdivided into a sufficiently large number 𝑛 of surface elements to achieve the desired spatial resolution. For the case of a gray enclosure the distribution factors are related to the temperatures and net heat fluxes from the surfaces according to

.. image:: https://github.com/mehranyarahmadi/Monte-Carlo-Ray-Tracing/blob/master/Eq%20(1).JPG

where

.. image:: https://github.com/mehranyarahmadi/Monte-Carlo-Ray-Tracing/blob/master/Eq%20(2).JPG

Figure below shows the logic block diagram of the Monte Carlo ray-trace method for gray,diffuse specular enclosures.

.. image:: https://github.com/mehranyarahmadi/Monte-Carlo-Ray-Tracing/blob/master/Algorithm.jpg

=============
Please Cite Our Paper
=============

Verification of Two-Dimensional Monte Carlo Ray-Trace Methodology in Radiation Heat Transfer Analysis
cite as: arXiv:1810.05204

=============
Contributing
=============

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. For typos, please do not create a pull request. Instead, declare them in issues or email the repository owner.

~~~~~~~~~~~
Final Note
~~~~~~~~~~~

We are looking forward to your kind feedback. Please help us to improve this open source project and make our work better. For contribution, please create a pull request and we will investigate it promptly. Once again, we appreciate your kind feedback and elaborate code inspections.
