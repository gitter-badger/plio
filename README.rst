===============================
Planetary Input / Output
===============================

.. image:: https://badges.gitter.im/USGS-Astrogeology/autocnet.svg
   :alt: Join the chat at https://gitter.im/USGS-Astrogeology/autocnet
   :target: https://gitter.im/USGS-Astrogeology/autocnet?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge

.. image:: https://img.shields.io/pypi/v/autocnet.svg
        :target: https://pypi.python.org/pypi/plio

.. image:: https://travis-ci.org/USGS-Astrogeology/plio.svg?branch=master
    :target: https://travis-ci.org/USGS-Astrogeology/plio

.. image:: https://coveralls.io/repos/USGS-Astrogeology/plio/badge.svg?branch=master&service=github
    :target: https://coveralls.io/github/USGS-Astrogeology/plio?branch=master

.. image:: https://readthedocs.org/projects/plio/badge/?version=latest
    :target: http://plio.readthedocs.org/en/latest/
    :alt: Documentation Status


A planetary file I/O API

Installation
------------
Installation is unfortunately complicated due to the difficulty in installing GDAL.  These are the steps that have been successfully tested on Linux and OSX.

1. Install Anaconda or Miniconda with Python 3.5
2. In your ~/.condarc file add the following two lines in the channels section.
   
    `- conda-forge`
    
    `- jlaura`
3. Create a new environment to ensure that the installed packge is not going to collide with existing packages
   
   ` conda create --name <somename> python=3`
   
3. Install `plio` with `conda install plio`.
