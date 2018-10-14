==============
RADIS Examples
==============

This project includes:

- Interactive examples to calculate infrared spectra of molecules with `RADIS <http://radis.readthedocs.io/>`__

- Static examples of fitting algorithm built around `RADIS <http://radis.readthedocs.io/>`__

Interactive Examples
--------------------

Run RADIS interactively directly from the browser. No installation needed!

1. `spectrum.ipynb <spectrum.ipynb>`_
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Manipulate a `Spectrum <http://radis.readthedocs.io/en/latest/source/radis.spectrum.spectrum.html#radis.spectrum.spectrum.Spectrum>`_ object:

.. image:: https://mybinder.org/badge.svg 
    :target: https://mybinder.org/v2/gh/radis/radis-examples/master?filepath=spectrum.ipynb
    :alt: https://mybinder.org/v2/gh/radis/radis-examples/master?filepath=spectrum.ipynb

2. `first_example.ipynb <first_example.ipynb>`_
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Calculate CO equilibrium and nonequilibrium spectra:

.. image:: https://mybinder.org/badge.svg 
    :target: https://mybinder.org/v2/gh/radis/radis-examples/master?filepath=first_example.ipynb
    :alt: https://mybinder.org/v2/gh/radis/radis-examples/master?filepath=first_example.ipynb

3. `radis_online.ipynb <radis_online.ipynb>`_
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Start a bare RADIS online session: 

.. image:: https://mybinder.org/badge.svg 
    :target: https://mybinder.org/v2/gh/radis/radis-examples/master?filepath=radis_online.ipynb
    :alt: https://mybinder.org/v2/gh/radis/radis-examples/master?filepath=radis_online.ipynb


Static Examples
---------------

`Install RADIS <https://radis.readthedocs.io/en/latest/install.html#install>`_ 
then run these examples locally. 


1. Multi Temperature Fit
~~~~~~~~~~~~~~~~~~~~~~~~

A 3 temperature fitting example reproducing the validation case of Klarenaar 2017 [1]_, who calculated a transmittance
spectrum from the initial data of Dang 1973 [2]_, with a 1 rotational temperature + 
3 vibrational temperature (Treanor distributions) model 

.. image:: docs/multi-temperature-fit.gif

CO2 Energies are calculated from Dunham developments in an uncoupled harmonic 
oscillator - rigid rotor model. The example is based on one of `RADIS validation cases <https://github.com/radis/radis/tree/master/radis/test/validation>`_. 
It makes use of the RADIS `Spectrum <http://radis.readthedocs.io/en/latest/#the-spectrum-class>`_
class and the associated compare and load functions

.. [1] Klarenaar et al 2017, "Time evolution of vibrational temperatures in a CO2 glow 
       discharge measured with infrared absorption spectroscopy" doi/10.1088/1361-6595/aa902e

.. [2] Dang et al 1982, "Detailed vibrational population distributions in a CO2 laser 
        discharge as measured with a tunable diode laser" doi/10.1007/BF00694640


Links
-----

- RADIS Documentation: http://radis.readthedocs.io/
- RADIS Source files: https://github.com/radis/radis
- PyPi project: https://pypi.python.org/pypi/radis
- Test status: https://travis-ci.org/radis/radis
- Test coverage: https://codecov.io/gh/radis/radis


