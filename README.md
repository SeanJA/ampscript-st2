AMPScript
====

It is an exact target creation, you can find the docs here: http://wiki.memberlandingpages.com/AMPscript/AMPscript_Syntax_Guide

I have some of the syntax hilighting working (code blocks, inline code, "constants"...).

INSTALL
====

1.  Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
1.  Open package control settings.
    *  ctrl-shift-p
1.  Search for `AmpScript Highlighter`
1.  If you're working with pasted text, make sure you select the syntax
    *  View > Syntax > ampscript-st2 > HTML(AMPScript)
1. Enojy :)

TODO
====
1.  Syntax hilighting in quotes in html attributes
1.  Tag Based Syntax
1.  Auto completion of code
1.  Snippets

Patches
====

Submit patches to the .JSON-tmLanguage files, not the xml files which are generated from them.

Build with AAAPackageDev and test against `test.amp`
