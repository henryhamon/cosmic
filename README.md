# COSmic
A Web-based editor for InterSystems Caché, inspired by [Ace](http://ace.c9.io) `(Ajax.org Cloud9 Editor)`.
COSmic uses [codemirror](http://codemirror.net) as editor.


### Installation

Find the latest release and import XML file into Caché by one of the next ways:

1. Just drag XML file over Studio window;
2. Go to the Management Portal -> System Explorer -> Classes -> Import and select the XML file;
3. Execute `do $system.OBJ.Load("C:\path\to\file\FileToImport.xml","ck")` in terminal.
