# nanoxml
NanoXML is a small non-validating parser for Java. NanoXML comes in different branches. Most branches are just a selection of classes in a common source tree.

* NanoXML/Java is the standard parser. This is the recommended branch for most users.
* NanoXML/SAX is a SAX adapter for NanoXML/Java. This branch is recommended for those who want to be independent of the parser or are already using SAX.
* NanoXML/Lite is the successor of NanoXML 1. It is still extremely small (only 6KB) and now features a much faster algorithm. It is recommended if you're currently using NanoXML 1 and don't want to adapt your code for the new API or if you're coding applications that have to be very small (like applets or embedded code). Please note that NanoXML/Lite has only limited functionality (no mixed content, DTD is ignored...).

The current version of NanoXML is 2.2.1, released April 3, 2002. 

This project is a Fork from http://nanoxml.sourceforge.net/orig/

### License [![zlib/libpng](https://raw.githubusercontent.com/saulhidalgoaular/nanoxml/master/license%20zlib-libpng.svg)](./LICENSE.txt)
nanoxml is published under the zlib/libpng license license.
