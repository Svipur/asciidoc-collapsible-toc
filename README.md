# AsciiDoc Collapsible Table of Contents

Collapsible Table of Contents (TOC) for AsciiDoc without external libraries and extensions. Uses a single docinfo.html file with a few lines of JavaScript and essential custom CSS.

## How to use

1. Place the docinfo.html file in the same folder as your AsciiDoc file.

2. Add the following attribute to the header of the AsciiDoc file: *:docinfo: shared*

3. Use with: *:toc: left* and *:toclevels: > 1*
