
.. _datacube-ecosystem:

Data Cube Ecosystem
===================

API Access from Jupyter
-----------------------
One of the most common ways to use Open Data Cube is through interactively
writing Python code within a Jupyter Notebook. This allows dynamically loading
data, performing analysis and developing scientific algorithms.

See :ref:`jupyter-notebooks` for some examples.


OGC Web Services
----------------

The datacube-ows_ server allows users to interact with
an Open Data Cube instance using client software (such QGIS, or the OpenLayers web mapping library), 
through the use of Web Map Service (WMS) and Web Coverage Service (WCS) standards from the Open Goespatial Consortium.


.. _datacube-ows: https://github.com/opendatacube/datacube-ows

Examples of this web server can be found in the `Australian National Map`_ service.

.. _`Australian National Map`: https://nationalmap.gov.au/#share=s-jfEZEOkxRXgNsAsHEC6xBddeS1b


Data Cube Explorer
------------------

`Data Cube Explorer`_ is a web application for searching and browsing the metadata
available from an Open Data Cube. It has rich visualisation abilities to show the
available data extents, and can be used to browse the provence of indexed data.

See the `Digital Earth Australia Explorer`_ for an example deployment showing the power of this tool.

.. _`Data Cube Explorer`: https://github.com/opendatacube/datacube-explorer
.. _`Digital Earth Australia Explorer`: https://explorer.sandbox.dea.ga.gov.au


Data Cube Stats
---------------

`Data Cube Statistics`_ is a an application used to calculate large scale temporal statistics on data stored using an Open
Data Cube installation. It provides a command line application which uses a YAML configuration file to specify the
data range and statistics to calculate.

.. _`Data Cube Statistics`: https://github.com/opendatacube/datacube-stats



Cube in a Box
-------------

`Cube in a Box`  provides everything needed to get up and running quickly with Open Data Cube inside
an Amazon Web Services Environment.

.. _`Cube in a Box`: https://github.com/opendatacube/cube-in-a-box


Command Line Interface
----------------------

Open Data Cube Core includes a powerful command line interface for managing data. It can:

 * Initialise indexes
 * Add products
 * Add datasets
 * Query available data
