= AsciiDoc Collapsible Table of Contents

Collapsible Table of Contents (TOC) for AsciiDoc without external libraries and extensions. Uses a single docinfo.html file with a few lines of JavaScript and essential custom CSS.

== How to use

. Place the docinfo.html file in the same folder as your AsciiDoc file.

. Add the following attribute to the header of the AsciiDoc file: __:docinfo: shared__

. Use with: __:toc: left__ and __:toclevels: > 1__
