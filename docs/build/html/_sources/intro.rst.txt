1. Get Started
================

1.1. Introduction
======================
The initial step is to install the necessary tool to run the application. The recommended tool for this purpose is Anaconda, which can be obtained from https://www.anaconda.com/. Ensure you choose the appropriate version compatible with your system.

Since this code is intended to be executed with ArcGIS Pro from ESRI, it is essential to first create an account and install the ArcGIS version available at https://www.arcgis.com/ or https://www.esri.com/. Make sure to have a valid license for ArcGIS.

Additionally, you'll need a text editor for coding. We suggest installing either Visual Studio Code from https://code.visualstudio.com/Download or Sublime Text from https://www.sublimetext.com/download.

We recommend the creation of a virtual environment using the file 'virtualVenv.yml' from the GitHub repository. Follow the steps below:

.. code-block:: python

  conda env create -f virtualVenv.yml

Activate 

.. code-block:: python

  conda activate WB_SRT

1.2. Set up
===================
Make sure that you have installed the arcpy library. If not, use the code below:
.. code-block:: python

  conda install arcpy=3.1 -c esri


To execute the code, run the code below:

.. code-block:: python

    run codefiles using c:\Progra~1\ArcGIS\Pro\bin\Python\scripts\propy.bat *path*.py

1.3. Data requirement 
=======================

* Market location spatial data
* River data 
* roads
* boundaries