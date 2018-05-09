====================
Changelog/Bug Fixes
====================

HyVR 0.2.1
----------

Release Date:

Contributors
""""""""""""

* Jeremy Bennett
* Samuel Scherrer
* Emilio Sanchez


Changes
"""""""

* Fixed bug in parsing of boolean options: previously all existing boolean
  options were parsed as ``True``
* Outputs for ParaView .vtr files are now specified with ``vtr`` instead of ``vtk`` as in previous versions.
* Some small changes to the testcase parameter file examples.
* Trends in porosity microstructure are now working.
* Architectural element lookup tables can now be saved to text files following simulation.
* Addition of ``virtual_boreholes`` function to ``HyVR.utils`` module. This can be used for generating borehole data from HyVR simulations.
* Some improvements to creation of MODFLOW 6 input files, including linear hydraulic head initial condition.
* Added testing functions.



HyVR 0.2
--------

Release Date: April 2018

Contributors
""""""""""""

* Jeremy Bennett
* Samuel Scherrer

Changes
"""""""

* First Release