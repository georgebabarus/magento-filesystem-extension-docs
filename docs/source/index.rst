
Magento file storage systems integration for media files
=========================================================

Use this Magento module to decouple files storage form compute systems and scale them independently.

Once you have base module installed and configured you can configure already developed storage systems driver, or develop yourself. A driver will be basically a class implementing basic operations: read/write files or directory.


.. toctree::
   :caption: General
   :numbered:
   :maxdepth: 2

   introduction
   installing
   configuration
   demo

.. toctree::
    :maxdepth: 2
    :numbered:
    :caption: Architecture

    architecture/architecture

.. toctree::
    :maxdepth: 2
    :numbered:
    :caption: Customization

    customization/extendable

.. toctree::
   :maxdepth: 2
   :caption: Changelog

   changelog


Latest releases
---------------


* V-0.2.2 - Alpha version

API references
--------------

Glossary
--------

Here are defined some principles you will find during the particular topics on this documentation.

.. glossary::
    WOOB
        Works out of the box - without any particular configuration then setting up the storage credentials.

    SWSCN
        Some web server configuration needed, with partial support.

    SWSCNO
        Some web server configuration needed **from performance** perspective, with partial support.

.. raw:: html
   :file: _static/analytics.html
