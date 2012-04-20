QuickWKT Qgis Plugin
====================

This Qgis Plugin makes it possible to show features in QGIS using WKT

This plugin is supposed to be installed via the plugin manager of QGIS
 
This project is managed by git

Code: https://github.com/elpaso/quickwkt

Plugin: http://plugins.qgis.org/plugins/QuickWKT/


Original Author: Alessandro Pasotti

Contributing Autors:

* Richard Duivenvoorde
* Ryan Lewis

License
-------

GPLv3


Version 1.8
-----------

- added example combo

Version 1.7
-----------

- fixed missing icon

Version 1.6
-----------

- add support for hexEWKB
- add support for linearring and geometry collections in WKT format


Version 1.5
-----------

- add more then one feature in the txt area, also a set of more geometry types
- create only layer type if needed: if you only paste a wkt of a point, then only a point layer is created
- lines which cannot be parsed combine to a warning
- user can either choose if the layers should be reused, OR on every use of plugin should create new layers
- addition of README

Version 1.0
-----------

- Initial version
