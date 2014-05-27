ESP Page Sample
===

This sample shows the features of ESP pages.

The ESP test page, index.esp, demonstrates the various ESP directives. These include:

* @@ to access request parameters/session variables
* @! to access local C variables
* <%= %> to emit the result of a C expression
* <%= %,d Number %> to use comma-separated number formatting
* <%= %S String %> to use safe-strings (HTML escape input)
* <%^start %> to emit code at the start of the generated page function
* <%^end %> to emit code at the end of the generated page function

Requirements
---
* [ESP](http://embedthis.com/downloads/esp/download.esp)

To run:
---
    esp run

The server listens on port 4000. Browse to: 
 
     http://localhost:4000/index.esp
     http://localhost:4000/

Code:
---
* [index.esp](index.esp) - ESP page to serve

Documentation:
---
* [ESP Documentation](http://embedthis.com/products/esp/doc/index.html)
* [ESP APIs](http://embedthis.com/products/esp/doc/api/esp.html)
* [ESP Guide](http://embedthis.com/products/esp/doc/guide/esp/users/index.html)
* [ESP Overview](http://embedthis.com/products/esp/doc/guide/esp/users/using.html)

See Also:
---
* [esp-controller - ESP Controller](../esp-controller/README.md)
* [esp-html-mvc - ESP HTML MMVC](../esp-html-mvc/README.md)
* [esp-layout - ESP Layouts](../esp-layout/README.md)