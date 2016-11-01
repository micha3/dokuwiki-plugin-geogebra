# dokuwiki-plugin-geogebra
Dokuwiki plugin for geogebra5 integration

As announced above this is a Dokuwiki plugin, designed for geogebra5 integration.
Is is an early try, so don't blame me for mistakes or low standard programming. :-)

Simply write something like
  \<ggb 480\>filename\</ggb\>
into your wiki's page, where filename must be the name of a file already uploaded. If you use namespaces for uploaded files,
replace all colons ":" by slashes "/".
The number (here: 480) indicates the height in pixels of the rendered geogebra frame.

To be able to render the frame correctly, a script (javascript) will be downloaded from geogebra.org. That's why a connection to
the internet is required. :-)
